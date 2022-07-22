# Paper-Categories-Prediction
In this repository, I fine-tuned the BERT pre-trained to perform the multi-label classification task on the  [dataset](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts) that contains the abstract, titles, and subject areas for papers in arXiv.

Different experiments were tried: 

- Using only "Abstracts" as single feature: 
  - with stemming. 
  - without stemming. 
  
  The training result shows that the loss function value without stemming is better than when doing stemming. 

- Using two inputs "Abstracts" and "Titles" to the BERT.

  The result shows that the two inputs give better accuracy than only a single feature.
