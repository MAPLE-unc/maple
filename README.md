# MAPLE

Code to train a classifier using MAPLE and estimate the uncertainty of prediction using Mahalanobis distance.
  

## Data structure

The dataset is arranged such that each class has a directory with the corresponding images placed in them. An example directory structure is shown below.

```bash
├── dataset
│   ├── train_data
│   │   ├── class1
│   │   ├── class2
...
│   │   ├── classN
│   ├── test_data
│   │   ├── class1
│   │   ├── class2
...
│   │   ├── classN

```
Each dataset is followed by a csv file containing the class name and the corresponding classification label. An example for CIFAR10 is given in `data/cifar10.csv`.

The dataset paths should be included in the `config.py`.  


## Training

The hyperparameters and arguments needed for training the network are available in `config.py`.
To launch the training, run 
```
python3 train.py
```

