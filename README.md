# Chicago Airbnb Data Analysis

<!-- TOC -->

- [Chicago Airbnb Data Analysis](#chicago-airbnb-data-analysis)
  - [Installation](#installation)
  - [Background](#background)
  - [File Descriptions](#file-descriptions)
  - [Results](#results)
  - [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

<!-- /TOC -->

## Installation

The code was developed using the Anaconda distribution of Python, versions 3.

## Background

In this project, I used open source Chicago Airbnb data (http://insideairbnb.com/get-the-data.html) to answer 4 business questions:

- Q1: How do listing information (description words, price per person per nignt) differ among different neiborhoods?
- Q2: Is there a general upward trend of both new Airbnb listings and total Airbnb visitors to Chicago?
- Q3: What are the busiest times of a year to visit Chicago? By how much do prices spike?
- Q4: What are the factors that explain the listing price the most?

These questions were answered using statistics, regression, and visualization.

## File Descriptions

There are 4 notebooks available here to showcase work related to the above questions. 

1. [`explore_part1.ipynb`](explore_part1.ipynb): load data and design new features based on the available dataset
2. [`explore_part2.ipynb`](explore_part2.ipynb): exploratory data analysis to answer Q1-Q3
3. [`model_part1.ipynb`](model_part1.ipynb): prepare data for regression analysis, including the handling of categorical variables and missing data
4. [`model_part2.ipynb`](model_part2.ipynb): train regression model and use the trained model to answer Q4

Markdown cells in each notebook were used to assist in walking through the thought process for individual steps.

## Results

The main findings of the code can be found at the post available [here](https://medium.com/@angangli/data-driven-insights-for-airbnb-rentals-in-chicago-8de4b95ce5ce).

## Licensing, Authors, Acknowledgements

Please find the Licensing for the dataset at Airbnb [data portal](http://insideairbnb.com/get-the-data.html). Other than that, feel free to play with the code here.