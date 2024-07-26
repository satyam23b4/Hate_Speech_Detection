# Hate_Speech_Detection

## Project Overview

This project involves analyzing tweets from a Twitter dataset to classify them as containing hate speech, offensive language, or neither. The project employs Decision Tree and Random Forest classifiers to perform the classification. The goal is to develop a model that can accurately identify harmful content on Twitter.

## Dataset

The dataset used in this project is a Twitter dataset, which includes the following columns:
- `count`: The number of times the tweet has been counted.
- `hate_speech`: The number of times the tweet has been flagged as hate speech.
- `offensive_language`: The number of times the tweet has been flagged as offensive language.
- `neither`: The number of times the tweet has been flagged as neither hate speech nor offensive language.
- `class`: The class label for the tweet:
  - 0: Hate
  - 1: Offensive Language
  - 2: Neither Hateful nor Offensive

## Requirements

To run this project, you need the following Python libraries:
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

You can install these packages using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
