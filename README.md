# GEO-Python-Week-2021

This repo was created for the Seismic Facies prediction with CNNs for the 2021 GeoPython Week.

## Salt Segmentation Tutorial

This tutorial is a copy a starter notebook https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277  
from the 2018 [TGS Kaggle Salt Identification challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge/)

The train data consist of 4000 (101 by 101) seismic patches and 4000 corresponding masks indicating regions of salt presence or not. The test data consist of 18000 (101 by 101) seismic patches. The dataset can be downloaded from the [competitions data page here](https://www.kaggle.com/c/tgs-salt-identification-challenge/)

The aim of the competition was to predict regions of salt or no salt on the test seismic patches.

In this example, we will be covering how to use th U-Net model (a popular type of image segmentation model) to identify salt regions from seismic image patches and the following;

* Loading the data
* Image resizing
* Training the U-Net
* Saving the trained model
* Prediction and Evaluation
* Visualizations