# NLP_Classification

## Table of contents
* [General info](#general-info)
* [Project 1: SMS Spam detection](#project-1---sms-spam-detection)
* [Project 2: Fake news detection](#project-2---fake-news-detection)
* [Project 3: Toxic comments detection](#project-3---toxic-comments-detection)

## General info
In this repository you'll learn how to classify text based on multiple models such as: Naive Baye, LSTM, Transformers (Bert) and One vs All

## Project 1 - SMS Spam detection

Using Naive Baye we have 98,56% accuracy ! (This is why companies use this algorithm for spams classification)

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150574725-1796aa22-348e-4763-a100-d422ef67cf52.PNG">
</p>

Using LSTM we have 97.72% accuracy, just like Naive Baye.

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150574731-ba2c0042-1fa4-4871-bab5-4d27f59b7aa4.PNG">
</p>

And using BERT we have 97.61% accuracy.

## Project 2 - Fake news detection

Using Naive Baye we have 62.92% accuracy and 54.07% of True news are misclassified as Fake news...

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150576073-f012070b-c34c-4218-aa96-3b16bc694863.PNG">
</p>

Using LSTM we have 67.16% accuracy and 50.00% of True news are misclassified as Fake news...

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150576076-05b8f3a1-df53-4df3-a580-a584e8f9fe0d.PNG">
</p>

Using BERT we have 65.20% accuracy, the algorithm doesn't learn much.

## Project 3 - Toxic comments detection

For this last project I am using the dataset from kaggle: <a href='https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification'>Jigsaw Unintended Bias in Toxicity Classification</a>

This project needs some changes in order to be perfect but we can already predict 'normal' and 'toxic' data very well.

Using Naive Baye we have for respectively normal and toxic data: 96.80% and 75.08% accuracy.

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150573359-655195b0-57a8-4c52-8d54-28edfaf0fce2.PNG">
</p>

Using LSTM we have for respectively normal and toxic data: 83.11% and 84.15% accuracy.

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150574157-b714308b-d388-4ff2-a136-68ac48066307.PNG">
</p>
