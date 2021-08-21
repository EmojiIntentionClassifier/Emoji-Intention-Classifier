# Emoji-Intention-Classifier

This repository contains the code and other supplements for the paper: **Why, Where and Who: On the Use of Emoji in Software Development Projects**.

## Overview
* ```code and supplements.zip``` contains survey questions and required code and data for running the classifier.
* ```training_data_generator.ipynb``` processes raw messages with emoji and outputs data for training the classifier. 
  - ```raw_train.txt``` and ```raw_label.txt``` can be used as test data for running the traininng data generator. 
  - Ouput will be stored in the ```test_data.csv``` format.
* ```random_forest.ipynb``` takes training data and outputs statistics and labeled result. 
  - It takes the ```test_data.csv``` format as input; instead, you can use ```data.txt``` as a more complete dataset to train the classifier.


