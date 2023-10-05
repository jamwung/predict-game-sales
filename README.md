# Video Game Sales Prediction

![Header](header.png)

Welcome to the Video Game Sales and Profitability Prediction project!

## About

This project is part of our machine learning course, representing my first attempt at implementing machine learning techniques on a passion project. It explores fundamental machine learning techniques, including data transformations, scaling, regression, and classification through linear models, decision trees, and non-parametric models. This implementation used the [Video Game Sales](https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset?select=Video_Games_Sales_as_at_22_Dec_2016.csv) dataset from Kaggle.

This implementation also leverages an automated machine learning pipeline from the [mltools repository](https://github.com/leolorenzoii/mltools).

## Summary

Video games are a popular form of interactive entertainment, enjoyed by both youth and adults. This study focuses on predicting video game sales based on their ratings. We utilize a dataset sourced from Kaggle and frame the problem in two ways:

1. **Video Game Sales Prediction via Regression**: We aim to predict the sales figures of video games.

2. **Video Game Profitability Prediction via Classification**: We categorize games into profitable and non-profitable based on predefined criteria.

## Highlights

- Regression problems can be transformed into classification problems by binning the target variable.
- Ratings are important predictors of video game sales, but popularity holds an even higher rank.
- Publishers play a crucial role in determining game profitability.

## Getting Started

To get started with this project, make sure you have the required dependencies installed. You can use the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.