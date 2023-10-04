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

Using Naive Baye we have 62.92% accuracy and 60.00% of True news are misclassified as Fake news...

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150576073-f012070b-c34c-4218-aa96-3b16bc694863.PNG">
</p>

Using LSTM we have 67.16% accuracy and 80.90% of True news are misclassified as Fake news...

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/150576076-05b8f3a1-df53-4df3-a580-a584e8f9fe0d.PNG">
</p>

Using BERT we have 65.20% accuracy, the algorithm doesn't learn much.

## Project 3 - Toxic comments detection

For this last project I am using the dataset from kaggle: <a href='https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification'>Jigsaw Unintended Bias in Toxicity Classification</a>

Using Naive Baye we have:
* 86.95% accuracy for normal data
* 33.39% accuracy for severe toxic data
* 19.23% accuracy for obscene data
* 35.06% accuracy for insults

For a total of 72.74% Accuracy.

This shows the limits of Naive Baye algorithm.

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/189272269-2320e2f3-3233-4c78-8a07-81f332221380.png">
</p>

Using LSTM we have:
* 91.18% accuracy for normal data
* 34.59% accuracy for severe toxic data
* 48.65% accuracy for obscene data
* 46.97% accuracy for insults

For a total of 76.78% Accuracy.

This is a great improvement from Naive Bayes.

<p align="center">
<img src="https://user-images.githubusercontent.com/65224852/189272275-b5c4a050-fc06-4c1f-8a9e-45165cb64cbc.png">
</p>

Using BERT we have 74% accuracy in total.
