# Lab-8: Adversarial Robustness Toolbox (ART)

## Introduction

ART is a library developed by "IBM Research" which is dedicated to adversarial machine learning. Its purpose is to allow rapid crafting and analysis of attacks and defense methods for machine learning models. ART provides an implementation for many state-of-the-art methods for attacking and defending classifiers. See below links for more information on ART.

    ART Demo: https://art-demo.mybluemix.net
    ART Blog: https://www.ibm.com/blogs/research/2018/04/ai-adversarial-robustness-toolbox/
    ART Github: https://github.com/IBM/adversarial-robustness-toolbox

In this lab, you will work with the Adversarial Robustness Toolbox (ART) and implement an adversarial attack and its defense on a trained model. You will work with a model trained on the German Traffic Signs dataset (see Citation below) and get the model to misclassify a stop sign.

## Dataset Citation

J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011.

@inproceedings{Stallkamp-IJCNN-2011,
author = {Johannes Stallkamp and Marc Schlipsing and Jan Salmen and Christian Igel},
booktitle = {IEEE International Joint Conference on Neural Networks},
title = {The {G}erman {T}raffic {S}ign {R}ecognition {B}enchmark: A multi-class classification competition},
year = {2011},
pages = {1453--1460}
}

## Objectives

Upon completing the lab, you will learn how to:

1. load a Tensorflow trained model
1. create an ART classifier object using the loaded model
1. perfom an adversarial attack
1. perfom a defense to make sure manipulated images can still be classified correctly

### Step 1. Please click on the link below to download the instructions to your machine.

[Instructions](https://github.com/bleonardb3/ML_POT_10-29-2020/raw/main/Lab-8/ARTv4.4.pdf).
