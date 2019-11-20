# Hotel Review Analysis

This project uses numpy, nltk and some machine larning tools to analyze online hotel reviews.

## Dataset
515K Hotel Reviews Data in Europe from [Kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe)

This dataset contains 515,000 customer reviews and scoring of 1,493 luxury hotels across Europe.

## Try it
Here are some steps for you to use pipenv with Jupyter notebook.

In the project folder, run:

```shell
$ pipenv install ipykernel
$ pipenv shell
```

This will bring up a terminal in your virtualenv like this:

```shell
(my-virtualenv) bash$
```

In that shell, run:

```shell
$ python -m ipykernel install --user --name=my-virtualenv
```

Don't forget to launch jupyter notebook:

```shell
$ jupyter notebook
```