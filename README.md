# Deterministic Uncertainty Quantification (DUQ)

## Description

This repository is a modification of [original repository](https://github.com/y0ast/deterministic-uncertainty-quantification) for [*Uncertainty Estimation Using a Single Deep Deterministic Neural Network (ICML 2020)*](https://arxiv.org/abs/2003.02037). This repository is for laboratory freshman and undergraduate students seminar in [MLILAB](http://mli.kaist.ac.kr).


## Download notMNIST dataset

```
mkdir -p data && cd data && curl -O "http://yaroslavvb.com/upload/notMNIST/notMNIST_small.mat"
```

## Download required libraries

```
pip install -r requirements.txt
```

## TODOs
- *TODO 1* : Fill in embed function in two_moons.ipynb and run two_moons.ipynb, two_moons_ensemble.ipynb to get confidence plots.
- *TODO 2* : Run train_duq_fm.py to get test accuracy and AUROC scores of MNIST dataset and notMNIST dataset.
- *TODO 3* : Run train_duq_cifar.py to get test accuracy AUROC score of SVHN dataset.
- *TODO 4* : Find best length_scale or l_gradient_penalties in train_duq_fm.py with respect to validation accuracy and AUROC.
- *TODO 5* : Replace two sided gradient penalty with one sided gradient penalty in two_moons.ipynb.