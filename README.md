# Fake News Detection Using Machine Learning

## Overview

This project implements a fake news detection system using machine learning. The model is trained to classify news articles as either fake or true based on their content. It uses a Naive Bayes classifier and TF-IDF vectorization for text processing.

## Project Structure

- `fake_news_detection.py`: Contains the code for training the model and classifying new news articles.
- 'Fake.csv`: CSV file containing fake news articles. Must include columns: `title`, `text`, `subject`, `date`.
- `True.csv`: CSV file containing true news articles. Must include columns: `title`, `text`, `subject`, `date`.

## Dependencies

- pandas
- scikit-learn
- numpy
- re (standard library for regex)

To install the required Python packages, you can use:

```bash
pip install pandas scikit-learn numpy

Usage
Prepare the Data:

Ensure your CSV files (path_to_fake.csv and path_to_true.csv) are formatted correctly with columns: title, text, subject, date.
Update the file paths in the code to point to your CSV files.
Train the Model.

Run the fake_news_detection.py script to train the model using the provided data.
Classify New Articles.

Use the classify_text function to classify new news articles. Provide the article content as input.

This will output whether the news article is classified as "Fake" or "True."




