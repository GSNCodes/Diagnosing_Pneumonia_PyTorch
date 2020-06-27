# Diagnosing_Pneumonia_PyTorch
Using PyTorch and CNNs to classify x-ray images that show traits of Pneumonia.

## Overview
In this project of mine, I employ the methods of Convolutional Neural Networks to classfiy x-ray images into the two following categories :-
* Pneumonia 
* Normal

I'll be implementing this using PyTorch. You can learn more about the code and process involved in achieving this in my article.

## Dataset
The dataset we'll be using is called "Chest X-Ray Images (Pneumonia)" by Paul Mooney and can be found on Kaggle using this [link](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). The dataset is organized into 3 folders (train, test, val) and contains sub-folders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) in total. It's around 1-GB, but you can use the notebook environment built into Kaggle if you do not want to download the file.
