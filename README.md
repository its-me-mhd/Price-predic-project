# Bulldozer Sale Price Prediction

## Overview
This repository contains a machine learning project aimed at predicting the sale price of bulldozers based on their characteristics and historical sale data. The project utilizes regression techniques to minimize the Root Mean Squared Log Error (RMSLE) and provides a comprehensive example of a machine learning workflow.

## Problem Definition
The goal is to predict the future sale price of bulldozers using their features and past sale prices. This involves building a model that can accurately estimate prices based on historical data.

## Data
The dataset is sourced from the Kaggle Bluebook for Bulldozers competition and includes three main files:

Train.csv: Training data with sales up to the end of 2011.

Valid.csv: Validation data with sales from January 1, 2012, to April 30, 2012.

Test.csv: Test data with sales from May 1, 2012, to November 2012.

Data Link: https://www.kaggle.com/c/bluebook-for-bulldozers/data

## Evaluation
The model's performance is evaluated using the RMSLE metric. The objective is to minimize this error to improve prediction accuracy.

Evaluation Details: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

## Features
The dataset includes various features related to bulldozers, such as:

Machine ID: Unique identifier for each bulldozer.

Sale Price: The target variable to predict.

Usage Band: The usage category of the bulldozer.

Machine Hours: The number of hours the bulldozer has been used.

Model Description: Description of the bulldozer model.

For a detailed description of all features, refer to the https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?gid=1021421956#gid=1021421956

## Dependencies
Python 3.x

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
