# PlantVillage Analysis

This repository contains the code and results in context of the paper titled **Using Deep Learning for Image-Based Plant Disease Detection**

####Organisation of code
The code for all the experiment configurations is arranged in directory structures across three different levels.

The first level is based on the choice of Deep Neural Network Architecture, which is divided into :

* AlexNet
* GoogleNet

Inside each of these folders, the second layer is based on the choice of dataset type, and the train-test split. The available options are :

* color-20-80
* color-40-60
* color-50-50
* color-60-40
* color-80-20
* grayscale-20-80
* grayscale-40-60
* grayscale-50-50
* grayscale-60-40
* grayscale-80-20
* segmented-20-80
* segmented-40-60
* segmented-50-50
* segmented-60-40
* segmented-80-20

And finally, inside each of these folders, the third layer is based on the choice of training approach, which is divided into:

* Traing From Scratch
* Finetuning (Transfer Learning)


All of these configurations lead to a total of **60** different experiment configurations.


#Author   

Tarun Kumar{<tarunkumarjee58@gmail.com>}




