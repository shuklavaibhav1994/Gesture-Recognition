# Gesture Recognition

## Problem Statement:

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. Below are the gestures:

<ul>
	<li>Thumbs up:  Increase the volume</li>
	<li>Thumbs down: Decrease the volume</li>
	<li>Left swipe: 'Jump' backwards 10 seconds</li>
	<li>Right swipe: 'Jump' forward 10 seconds</li>
	<li>Stop: Pause the movie</li>
</ul>

## Objective

The objective is to train multiple models to correctly identify each gesture. We have to build two kind of models which are 1) Conv3D and 2) Conv + LSTM/Conv + GRU. Accuracy metrics will be used to check which model is performing better. The model will be trained on training data and validate on validation data. Finally after building multiple models, h5 file of the best model needs to be saved which will be used to check the performance on test data.	

## Technologies Used: 

Python, HTML

## Libraries Used: 

Numpy, Pandas, Tensorflow, Keras, CNN, RNN

## Steps covered:

<ul>
	<li>Data Preparation</li>
	<li>Generator Function</li>
	<li>Model Building</li>
	<li>Observations</li>
</ul>

## Contributors

<ul>
	<li><b>Facilitator:</b> Vaibhav Shukla</li>
	<li><b>Group Member:</b> Pankaj Sharma</li>
</ul>