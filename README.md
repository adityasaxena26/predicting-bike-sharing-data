# Deep Learning Nanodegree
## Neural Network
## Project: Predicting Bike Sharing Data

## Project Overview
This project is a part of Udacity's Deep Learning Nanodegree Program. In this project, you'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! The model will predict daily bike rental ridership. By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher level tools such as Tensorflow. You'll also get to see how to apply these networks to solve real prediction problems!

## Software and Libraries
- Download anaconda or miniconda.
- Create a new conda environment:

  conda create --name dlnd python=3

- Enter your new environment:

  Mac/Linux: >> source activate dlnd

  Windows: >> activate dlnd

- Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:

  conda install numpy matplotlib pandas jupyter notebook

- Run the following to open up the notebook server:

  jupyter notebook

- In your browser, open my_first_neural_network.ipynb

- Follow the instructions in the notebook; they will lead you through the project. You'll ultimately be editing the my_answers.py python file, whose components are imported into the notebook at various places.


## Data
The data comes from the UCI Machine Learning Database.https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.

### Dataset characteristics
=========================================
Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv

- instant: record index
- dteday : date
- season : season (1:springer, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
+ weathersit :
 - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
 - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
 - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
 - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are divided to 41 (max)
- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered
