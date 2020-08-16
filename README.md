# COVID19 Classification using Chest XRay

Inspired by [Adrian Rosebrock's blog - 'Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning
'](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)

## Disclaimer:
**The methods and techniques used in this post are meant for educational purposes only. This is not a scientifically rigorous study, nor will it be published in a journal. This article is for people who are interested in (1) Computer Vision/Deep Learning and want to learn via practical, hands-on methods and (2) are inspired by current events. I kindly ask that you treat it as such.**

This repository contains one notebook solving the use case, which uses FastAI library.

## About FastAI
Fast.ai is a brainchild of Rachel Thomas and Jeremy Howard. The idea behind FastAI is to democratize AI to reach people from all domains.

Keras is another library, built on top of TensorFlow and therefore provides abstraction over Google's TensorFlow. Although, being very powerful, it still requires you to write a lot of lines of code to get things done. Therefore, to quickly get started with experimentation, FastAI is good and my personal preference.

## About Dataset

The dataset used in this use-case is from [Kaggle - 'COVID-19 RADIOGRAPHY DATABASE (Winner of the COVID-19 Dataset Award)
'](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)


## Key Takeaways

In this usecase, we are going to determine how easy it is to use Computer Vision techniques with FastAI library to classify images of XRays, which are not very easy with human eyes. With just ~3000 images, we will be able to determine whether a patient is COVID Positive or just has Viral Pneumonia or is NORMAL.

**Note: Again, this is not a scientifically rigorous study, nor will it be published in a journal and should only be referred to for educational purposes.**

#### Thank You
