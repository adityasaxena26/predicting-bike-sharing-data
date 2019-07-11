# Udacity Deep Learning Nanodegree
## Neural Network
## Project: Predicting Bike Sharing Data

## Project Overview
This project is a part of Udacity's Deep Learning Nanodegree Program. In this project, I built a neural network from scratch to carry out a prediction problem on a real dataset! The model will predict daily bike rental ridership. By building a neural network from the ground up, you'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher level tools such as Tensorflow. You'll also get to see how to apply these networks to solve real prediction problems!

## Data
The data comes from the UCI Machine Learning Database.https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.

### Dataset characteristics

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
* weathersit :
    * 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    * 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    * 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    * 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are divided to 41 (max)
- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

### Software and Libraries
* [Python 2.7 or higher](https://www.python.org/downloads/)
* [NumPy](https://pypi.org/project/numpy/)
* [Matplotlib](https://pypi.org/project/matplotlib/)
* [Pandas](https://pypi.org/project/pandas/)
* [Jupyter Notebook](https://jupyter.org/install)

### Project Instructions

- Clone the repository and navigate to the downloaded folder.

 `git clone https://github.com/adityasaxena26/predicting-bike-sharing-data.git`

 `cd predicting-bike-sharing-data`
- Run the following to open up the notebook server:`jupyter notebook`

- In your browser, open `my_first_neural_network.ipynb`

- Edit the `my_answers.py` python file, whose components are imported into the notebook at various places.
