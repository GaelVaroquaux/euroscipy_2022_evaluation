# EuroSciPy 2022 - Evaluating your ML models tutorial

Follow the intro slides [here](https://www.slideshare.net/GaelVaroquaux/evaluating-machine-learning-models-and-their-diagnostic-value).

## Follow the tutorial online

Launch an online notebook environment using [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ArturoAmorQ/euroscipy_2022_evaluation/HEAD)

- [1_evaluation_tutorial.ipynb](https://mybinder.org/v2/gh/ArturoAmorQ/euroscipy_2022_evaluation/HEAD?labpath=notebooks%2F1_evaluation_tutorial.ipynb)
- [2_roc_pr_curves_tutorial.ipynb](https://mybinder.org/v2/gh/ArturoAmorQ/euroscipy_2022_evaluation/HEAD?labpath=notebooks%2F2_roc_pr_curves_tutorial.ipynb)
- [3_uncertainty_in_metrics_tutorial.ipynb ](https://mybinder.org/v2/gh/ArturoAmorQ/euroscipy_2022_evaluation/HEAD?labpath=notebooks%2F3_uncertainty_in_metrics_tutorial.ipynb)

You need an internet connection but you will not have to install any package
locally.

## Running the tutorial locally

### Dependencies

The tutorials will require the following packages:

* python
* jupyter
* pandas
* matplotlib
* seaborn
* scikit-learn ! **version >= 1.2.dev0** (still in development as of august 2022)

### Local install

We provide both `requirements.txt` and `environment.yml` to install packages.

You can install the packages using `pip`:

```
$ pip install -r requirements.txt
```

You can create an `evaluation-tutorial` conda environment executing:

```
$ conda env create -f environment.yml
```

and later activate the environment:

```
$ conda activate evaluation-tutorial
```

You might also only update your current environment using:

```
$ conda env update --prefix ./env --file environment.yml  --prune
```
