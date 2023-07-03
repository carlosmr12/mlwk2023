# Computing for Life Sciences 2023
## Machine Learning Workshop - Exploring small molecule potency

by [@carlosmr12](https://twitter.com/carlosmr12) & [@alexgcsa](https://twitter.com/alexgcsa)

## Colab Notebooks

The material is divided into classification and regression and can be accessed via Google Colab Notebooks:
- [Classification colab](https://colab.research.google.com/github/carlosmr12/mlwk2023/blob/master/lecture1_classification.ipynb)
- [Regression colab](https://colab.research.google.com/github/carlosmr12/mlwk2023/blob/master/lecture2_regression.ipynb)

## Local installation

Alternatively, if you want to run it locally, we suggest you use [anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.

1. First create an environment with the following command:

```bash
$ conda create -n workshopml
```

2. Then, install dependencies via pip:


```bash
$ conda activate workshopml

$ conda install python=3.10

$ pip install -r requirements.txt
```

3. And finally, running the notebook

```bash
$ conda activate workshopml

$ jupyter lab
```
