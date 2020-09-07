# Stock Price Sentiment Prediction

![Python 3.6.12](https://img.shields.io/badge/Pyhton-3.6.12-blue) ![Flask](https://img.shields.io/badge/Flask-1.1-orange) ![Heroku](https://img.shields.io/badge/Heroku-Deployment-brightgreen)

## Objective

The objective of this project is to predict the <strong>stock price sentiment</strong> of a company based on top recent news headlines about the company.

## Live Demo

<a href="https://stock-sentiment-prediction.herokuapp.com/">Stock Price Sentiment Predicition</a>

  ### Glimpse of the Web App
  <br>

  ![GIF](stocksentiment.gif)

## Installation
The Code is written in Python 3.6.12. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── data
├── models
├── static 
│   ├── fall.png
│   ├── raise.png
│   ├── style.css
├── templates
│   ├── index.html
│   ├── result.html
├── Procfile
├── README.md
├── Stock Sentiment Analysis.ipynb
├── app.py
├── requirements.txt
```

## Dataset

The dataset is taken from kaggle. This dataset contains historical news headlines crawled from Reddit WorldNews Channel (/r/worldnews). The dataset link is given <a href="https://www.kaggle.com/aaron7sun/stocknews">here</a>.

## Code

The code for the model, algorithms used and accuracy of the model can be found <a href="https://github.com/VarunV991/Stock-Price-Sentiment-Analysis/blob/master/Stock%20Sentiment%20Analysis.ipynb">here</a>.

## Web App and Deployment

This project uses Flask for the web app and its deployment is done on Heroku.

#### Other Info
This project is a modified version of an older project on the same topic.The original project is available <a href="https://github.com/krishnaik06/Stock-Sentiment-Analysis">here</a>.
