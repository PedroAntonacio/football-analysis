# Football Data Analysis

An analysis of the evolution of football based on international matches data from the past 150 years.

## Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation

For this project, I was interestested in using international football matches data from 1872 to 2021 to better understand:

1. How has football grown over time?
2. Was the growth similar in all continents?
3. Has the playing style changed throughout the years?

## Dataset

This project used the ["International football results from 1872 to 2021"](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017) dataset, publicly available on Kaggle. This dataset contains over 40,000 results of men international football matches starting from the very first official match in 1872 up to 2021. After downloading the dataset from Kaggle, the `results.csv` and `shootouts.csv` files should be extracted in the [`./data`](./data) folder.

Additionally, I manually built the [`contry-to-confederation.csv`](./data/contry-to-confederation.csv) table to match countries to their respective FIFA Confederations. This table is available in the [`./data`](./data) folder.

## Run

To execute the code, run the [`football-analysis.ipynb`](./code/football-analysis.ipynb) notebook in the [`./code`](./code) folder.

## Results

The findings of this project are detailed in the [`ANALYSIS.md`](./ANALYSIS.md) file in this repository.

## Licensing

Feel free to use the code here as you would like!