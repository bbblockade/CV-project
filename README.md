# code for TTL image pairing task

Name: Jiqiang Chen
Nane: Haoran Li
For naive approach, run 'naive approach'
For siamnese approach, run 'preprocess' first, then run either 'train_res18' or 'train_res50', and predict with 'predict'
# Code structure

- **data selection.ipynb**
  - Code for select hard negatives in training set using pretrained model
- **naive approach.ipynb**
  - no-training method by applying pretrained model directly on test set
- **pair.csv**32
  - selected hard negatives for training
- **preprocess.ipynb**
  - preprocess the tensor for training and predicting, the default image file address is applied, it can be also specify with other address

- **train_res18.ipynb**
  - training process for res18 siamese network

- **train_res18.ipynb**
  - training process for res18 siamese network

- **predict.ipynb**
  - predict process of siamese network for Kaggle challenge format
