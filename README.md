# Malaria Detection Using CNN(Keras & Google Colab)

<p align="center">
<img src=https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcR6PgM9K6Vh5NMk8EwuPW3u1-k1aMLkSLnBvYAAM3nsUuff-NYs&usqp=CAU width=300 height=200>
</p>

When new to CNN and deep learning we often find it difficult to find correct resources to get stated. This code will hel you get started in the easiest manner and will help you gain poerspective of how CNN works and different elements of CNN

To get started please download the data from:

[Malaria Cell Images Download](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)

<p align="center">
<img src=https://cdn-images-1.medium.com/max/1000/1*2xrFaqUUjPiTjf-Gnt3Vnw.png width=300 height=300>
</p>

***Step-1***

To get started we need to have a google colab account or just sign in to google colab

***Step-2***

Place the downloaded data to a place in gDrive mine was stored as *cell_images.zip* in  *Malaria-Detection* folder in my gDrive

***Step-3***

We need to unZip and bring the data in colab environment

***Step-4***

Read in the data and store it in array format. Here, you can choose whatever shape you like, I have restricted it to 64x64. If we increase the image size the total file size will increase drastically and we might run out of resources to while running our CNN Model

***Step-5***

After conversion of the dataset and getting final array, we save it for further use.

***Step-6***

Define a CNN model based on your learning or exploration. Add as Conv2d layers, Dropouts and MaxPooling layers, you can also try padding and stride. Just check the hyperparameters for Conv2D

***Step-7***

Basic implementaion of model has been done in the code, you can play around with # of Epochs or batch size or the optimizer altogether.

Please go through the attached code in detail to get the idea of CNN, Malaria Detection using Google Colab
