Activity Classification

# Contents

1. [Requirements](https://github.com/sadra-safa/ActivityClassification/blob/master/README.md#requirements)
2. [Datasets](https://github.com/sadra-safa/ActivityClassification/blob/master/README.md#datasets)
3. [Run](https://github.com/sadra-safa/ActivityClassification/blob/master/README.md#run)

# Requirements
This project depends on  `numpy`, `scikit-learn` and `PyTorch` packages.
They can be installed as:

```
pip install numpy scikit-learn
conda install pytorch torchvision torchaudio pytorch-cuda=11.6 -c pytorch -c nvidia
```
For installing different versions of `PyTorch` please check [the official PyTorch webiste](https://pytorch.org/)

# Datasets
1. Downlaod the "Activity recognition using wearable physiological measurements" dataset from [here](https://www.mdpi.com/1424-8220/19/24/5524/s1)
2. Download the "UCI Har Dataset" dataset from [here](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)
3. Extract these datasets into the `Datasets` folder.
4. The directory structure should be like the following:
```
├── ActivityClassification
    ├── Datasets
        ├── sensors-19-05524-s001_new
            ├── data.txt
            ├── info.txt
            ...
        ├── UCI HAR Dataset
            ├── train
            ├── test
            ...
    ├── wearable.ipynb
    ├── smartphone.ipynb
```
These steps can be performed using the following commands:
```
wget -O wearable.zip --user-agent="Mozilla" https://www.mdpi.com/1424-8220/19/24/5524/s1
wget https://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.zip
unzip wearable.zip
unzip 'UCI HAR Dataset.zip'

```

# Run
Run `wearble.ipynb` and `smartphone.ipynb` for the first and second dataset respectively.
