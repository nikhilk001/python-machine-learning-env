# python-machine-learning-env

[Docker](https://hub.docker.com/r/dev010/python-machine-learning-env) image with python .. for Machine Learning, Artificial Intelligence, Deep Learning & AIML pipeline projects. This image contains python, conda and top 15 Machine learning libraries like numpy, pandas, scikit-learn, matplotlib, seaborn, tensorflow, keras, xgboost, nltk, scipy, gensim, spacy, beautifulsoup4, requests, flask.

Uses Conda installed with [Miniconda](https://hub.docker.com/r/continuumio/miniconda3)

To install any extra package use .

```bash
conda install --quiet --yes tensorflow
```


[Github repo](https://pip.pypa.io/en/stable/)
[Docker hub](https://github.com/nikhilk001/python-machine-learning-env)

## How to use

You don't need to clone the GitHub repo. You can use this image as a base image for other images, using this in your Dockerfile:

```python
FROM python-machine-learning-env:python3.11

COPY ./main.py /app/main.py
