## Hosted at AWS EC2 
 http://ec2-18-133-180-187.eu-west-2.compute.amazonaws.com:8080/
1


# Flight Price Predictor

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [License](#license)
  * [Credits](#credits)


## Demo
[![](https://github.com/milangeorge2000/Mammootty_Mohanlal_Classifier/blob/main/static/ee575888-1427-410c-8d68-c41bf58afa86.jpg?raw=true)](https://github.com/milangeorge2000/Mammootty_Mohanlal_Classifier/blob/main/static/d3b760c1-857b-48fa-bf96-f53ef273b9c9.jpg?raw=true)

## Overview
This is a simple flask application which predicts the price of a flight when the required parameters are given as input.

## Motivation
I was always in a thought process of on what terms the flights are charging their price and how the flight price varies. After learning ML thought of how to build a web app that could predict the price of flight.

## Technical Aspect
All the main aspects of a Data Science Project is Done here which inlucdes:
1. Exploratory Data Analysis
2. Feature Engineering
3. Feature Selection
4.Training
5.Testing
6.Deployment

## Installation
The Code is written in Python 3.7.10 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Run

To run the app in a local machine, shoot this command in the project directory:
```bash
python app.py
```

## Deployement on Heroku
.[[Reference](https://medium.com/@nutanbhogendrasharma/deploy-machine-learning-model-with-flask-on-heroku-cd079b692b1d)]

## Directory Tree 
```
├── app 
│   ├── app.py
│   ├── flight_price.pkl
│   ├── static
│   └── templates
├── requirements.txt
├── LICENSE
├── Procfile
├── README.md
├── flight_price_prediction.ipynb
├── runtime.txt
```

## To Do
1. To add more cities 

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/milangeorge2000/flight_price_prediction/issues) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/milangeorge2000/tinkerhub/issues/new). Please include sample queries and their corresponding results.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://pytorch.org/tutorials/_static/img/thumbnails/cropped/profiler.png" width=200>](https://pytorch.org/) [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://miro.medium.com/max/750/1*q6F0j8HFHd8jeYXyQBqrCQ.jpeg" width=200>](https://aws.amazon.com/ec2/)

## License
[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0e)

Copyright 2021 Milan Varghese George

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Credits
- My Sincere thanks to Krish Naik for showing the way
