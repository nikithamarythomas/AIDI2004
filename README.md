# Breast Cancer Detection Models

## Introduction

This repository contains code for training and evaluating classification models for breast cancer detection tasks.


## Usage

### Prerequisites

- Python 3
- Jupyter Notebook
- scikit-learn
- Matplotlib (for visualization, if needed)

### Installation

You can install the required packages using pip:
```python
pip install scikit-learn numpy matplotlib jupyter
```

###  Regression Models 

1. Clone this repository:

```bash
git clone https://github.com/nikithamarythomas/AIDI2004.git
```
Main branch : Logistic Regression
Branch 'branch' : SVM

Launch the notebook in your preferred IDE to use the models.


## Dataset

Both models are trained and evaluated on the Breast Cancer Wisconsin (Diagnostic) Dataset, available in scikit-learn's datasets module. The goal to predict whether the mass is benign or malignant.

## NOTE 

When working with Jupyter Notebook files (.ipynb), you can use nbdiff to visualize Git diffs more effectively.
<br>*nbdiff* is a tool that provides a rich visualization of differences between Jupyter Notebooks. You can install it via pip:

```bash
pip install nbdime
```

Integrate nbdiff with git:

```bash
nbdime config-git --enable
```

After configuration, you can use git diff as usual, and nbdime diff will provide a human-readable diff: