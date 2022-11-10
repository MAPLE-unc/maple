# MAPLE

Code to train a classifier using MAPLE and estimate the uncertainty of prediction using Mahalanobis distance.
  

## Data structure

The dataset should be arranged such that each class has a directory with the corresponding images placed in them.

+-- _config.yml
+-- _drafts
|   +-- begin-with-the-crazy-ideas.textile
|   +-- on-simplicity-in-technology.markdown


## Training

The hyperparameters and arguments needed for training the network are available in `config.py`.
To launch the training, run 
```
python3 train.py
```

