# NLP Sentiment Analysis on Customer Reviews

![NLP Sentiment Analysis](nlp-sentiment-analysis.png)

Welcome to the **NLP Sentiment Analysis on Customer Reviews** Git repository! In this project, I perform sentiment analysis on customer reviews using the popular IMDB dataset. I employ both the Long Short-Term Memory (LSTM) neural network and the XGBoost machine learning algorithm to analyze and predict the sentiment of customer reviews.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [LSTM Model](#lstm-model)
- [XGBoost Model](#xgboost-model)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment or emotion expressed in a piece of text. In this project, I focus on sentiment analysis of customer reviews using the IMDB dataset, which contains movie reviews labeled as positive or negative.

I implement two different approaches for sentiment analysis: a deep learning approach using LSTM and a traditional machine learning approach using XGBoost. Both models are trained on the IMDB dataset to predict whether a customer review is positive or negative.

## Dataset

The IMDB dataset consists of 50,000 movie reviews that are split into 25,000 reviews for training and 25,000 reviews for testing. Each review is labeled as either positive or negative sentiment.

Dataset: [IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

## Project Structure

The repository is organized as follows:

- `data/`: Contains the IMDB dataset and any additional data required for training and testing.
- `models/`: Includes the trained LSTM and XGBoost models.
- `notebooks/`: Jupyter notebooks for data exploration, model training, and evaluation.
- `scripts/`: Python scripts for preprocessing, training, and deploying the models.
- `app/`: Web application files for model deployment.
- `requirements.txt`: Lists all the required packages and dependencies.

## LSTM Model

The LSTM (Long Short-Term Memory) model is a type of recurrent neural network (RNN) that is well-suited for sequence data, such as text. I use the LSTM model to learn the patterns and relationships in the text data to make sentiment predictions.

## XGBoost Model

XGBoost is a powerful machine learning algorithm known for its performance and flexibility. It's particularly effective for tabular data and can capture complex relationships in the input features.

## Deployment

The sentiment analysis models are deployed using a web application built with Flask. The `app/` directory contains the necessary files to run the web application locally.

## Usage

1. Clone this repository: `git clone https://github.com/your-username/nlp-sentiment-analysis.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the data preprocessing, model training, and evaluation processes.
4. Train and save the LSTM and XGBoost models using the provided scripts in the `scripts/` directory.
5. Run the Flask web application in the `app/` directory to deploy the models locally.

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

I hope you find this repository informative and useful for your journey into sentiment analysis with NLP. If you have any questions or feedback, don't hesitate to reach out. Happy coding! 🚀
