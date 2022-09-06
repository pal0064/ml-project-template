# Cookiecutter DS/ML Project Template

_A logical, reasonably standardized, but flexible project structure for doing and sharing DS/ML work._


## Requirements to use the cookiecutter template

 - Python 2.7 or 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
pip install cookiecutter
```

or

``` bash
conda config --add channels conda-forge
conda install cookiecutter
```
or 

``` bash
brew install cookiecutter
```

## Installing development requirements

    pip install -r requirements.txt

## To start a new project, run:

    cookiecutter gh:pal0064/ml-project-template

If this doesn't work try using SSH with the full path:

```
cookiecutter git+ssh://git@github.com/pal0064/ml-project-template
```


## The resulting directory structure

The directory structure of your new project looks like this: 

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── datasets
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── final          <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── docs               <- Code documentation and generated analysis as HTML, PDF, LaTeX, etc.
│   └── images         <- Generated graphics and figures to be used in reporting
|   └── reports        <- Generated analysis as HTML, PDF, LaTeX, etc.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
|__ output             <- Temporary Output files
```

## Acknowledgements
- [drivendata/cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science)


License
-------

This project is licensed under the terms of the [MIT License](/LICENSE)
