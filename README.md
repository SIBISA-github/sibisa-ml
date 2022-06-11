# SIBISA - Machine Learning Model
> This is a repository for building the Machine Learning model for the SIBISA application, a sign language learning app for Indonesia language (SIBI)

## Table of contents
* [Description](#description)
* [Datasets](#datasets)
* [Architecture](#architecture)
* [Link to papers related](#link-to-papers-related)

## Description
This machine learning model is built to predict the sign language of the user. The model's task is to detect and also classify the hand gestures of the user. The model is built based on tensorflow and keras.

## Datasets
The dataset is gathered from kaggle and gathered by our team. These are the following links:
- https://www.kaggle.com/datasets/salsabilayuganto/sibi-sistem-bahasa-isyarat-indonesia
- https://www.kaggle.com/datasets/mlanangafkaar/datasets-lemlitbang-sibi-alphabets

The dataset gathered by our team is labeled using labelImg https://github.com/tzutalin/labelImg

## Architecture
The model is based on Single Shot Detector and MobileNet V2 Architecture. The model is trained using the dataset gathered from kaggle.

https://tfhub.dev/tensorflow/ssd_mobilenet_v2/fpnlite_320x320/1

## Link to papers related
- SSD : https://arxiv.org/abs/1512.02325
- MobileNet V2 : https://arxiv.org/abs/1801.04381
