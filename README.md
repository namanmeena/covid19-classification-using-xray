# COVID19 Classification using Chest XRay

Inspired by [Adrian Rosebrock's blog - 'Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning
'](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)

## Disclaimer:
**The methods and techniques used in this post are meant for educational purposes only. This is not a scientifically rigorous study, nor will it be published in a journal. This article is for people who are interested in (1) Computer Vision/Deep Learning and want to learn via practical, hands-on methods and (2) are inspired by current events. I kindly ask that you treat it as such.**

This repository contains one notebook solving the use case, which uses FastAI library.

## About FastAI
Fast.ai is a brainchild of Rachel Thomas and Jeremy Howard. The idea behind FastAI is to democratize AI to reach people from all domains. They have created a complex but simple to use library which does all the heavy lifting for you so that you can focus on building the model and domain specific nuances and not worry too much about setting things up. Fast AI offers much more abstraction than Keras. Keras as you might know is built over Tensorflow whereas Fast AI is built over PyTorch. To illustrate the level of abstraction provided by Fast AI compared to Keras, a 31 line code in Keras to setup resnet50 model requires just 5 lines of code in Fast AI! Fast AI allows you to build learning models at a blazingly fast pace. I’ve recently started learning fast.ai and classifying x-ray images is one of the 3–4 different classifier models I was able to create in a couple of days.

Keras is built on top of TensorFlow and therefore provides abstraction over Google's TensorFlow, but being so powerful, it still requires you to write a lot of lines of code to get things done. Therefore, to quickly setup and experiment and analyze, FastAI is my go to preference.

## About Dataset

The dataset used in this use-case is from [Kaggle - 'COVID-19 RADIOGRAPHY DATABASE (Winner of the COVID-19 Dataset Award)
'](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)
