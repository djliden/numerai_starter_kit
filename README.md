# Numerai Starter Kit
A quick template for getting started with Numerai and numerapi in a google Colab notebook

To get started immediately, check out the [colab notebook](https://colab.research.google.com/github/djliden/numerai_starter_kit/blob/main/Numerai_Starter_Kit.ipynb)!

This repository contains resources for getting started with [numerai](numer.ai) in a [Google Colab](colab.research.google.com) environment. In particular, it shows how to download and access the data and submit predictions using the [numerapi](https://github.com/uuazed/numerapi) package and contains a couple of sample models that generate working submissions.

It is specifically intended to address two particular pain points for new users:
- Uploading predictions using your API keys; and 
- Parsing large data files that, if read all at once, will not fit in a google colab session's memory.
