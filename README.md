# Bank-Notes-Authenticator

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![Scikit-Learn](https://img.shields.io/badge/Library-ScikitLearn-orange.svg)

This repository consists of files required for end to end implementation and deployment of Machine Learning Bank Notes Authenticator web application created with flask and deployed on Heroku platform.

## Table of Contents
  * [App Link](#app-link)
  * [About the App](#about-the-app)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)
  


## App Link
If you want to view the deployed model, click on the following link:<br />
[https://banknotesauthenticatorapp.herokuapp.com/](https://banknotesauthenticatorapp.herokuapp.com/)

A glimpse of the web app:

![image](https://user-images.githubusercontent.com/78199382/112984375-6fa52c00-917c-11eb-9853-c27122efbf60.png)

## About the App
The Bank Notes Authenticator is a flask web application which detects whether the bank notes are authentic or not based on certain parameters like variance, skewness, curtosis, and entropy. The code is written in Python 3.6.10. 

As per the research, for values of variance between –3.3203 and –0.4080 and having skewness <= 0.7201, the model includes one more predictor Entropy, which detects that approximately 95% of banknotes are Fake if their entropy values are less than or equal to -0.2077, while for the entropy values greater than –0.2077 have 100% fake banknote  detection. Furthermore, for variance between –0.4080 and 0.4957 and Kurtosis less than –0.1965, 71% of fake banknotes can be  predicted  and for value of Kurtosis greater  than –0.1965,  75% of Genuine banknotes can be detected. Similarly other decision conditions are made based on independent variable chosen in the model which helps in classifying the fake banknote from genuine banknotes.

If you don't have Python installed, you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually to deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

The next step would be to follow the instruction given in the [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 





