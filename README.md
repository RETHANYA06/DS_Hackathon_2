# OTT Show Success ML Analysis

## Project Overview

This project analyzes OTT show-level data to understand the characteristics associated with successful and less-successful shows.

The analysis focuses on genre, language, runtime, release year, budget, rating, and viewership. A Random Forest model is also used to classify shows as successful or less successful.

## Dataset

The dataset contains 100 OTT shows with the following attributes:

* Show ID
* Genre
* Language
* Runtime
* Release Year
* Budget
* Rating
* Viewership

## Analysis Performed

* Data validation and exploratory data analysis
* Descriptive statistics
* Successful vs less-successful show distribution
* Genre performance analysis
* Rating vs viewership analysis
* Language performance analysis
* Identification of characteristics associated with strong performance
* Content-performance visualizations

## Visualizations

The project includes 4 visualizations:

1. Successful vs Less-Successful Shows
2. Average Viewership by Genre
3. Rating vs Viewership
4. Average Viewership by Language

## Machine Learning

**Algorithm:** Random Forest Classifier

The model predicts whether a show is classified as **Successful** or **Less Successful**.

Viewership was excluded from the model features because it was used to define the success category.

## Model Evaluation

| Metric                      | Result |
| --------------------------- | -----: |
| Accuracy                    |    95% |

## Project Files

* `ottshow_cleaned_dataset.csv` — Cleaned dataset
* `OTT_Show_Success_Analysis.ipynb` — Python/Colab analysis
* `OTT_Show_Success_Analysis.pdf` — Project report
* `README.md` — Project documentation
