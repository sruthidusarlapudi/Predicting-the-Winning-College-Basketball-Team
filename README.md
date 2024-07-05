# Predicting the Winning College Basketball Team

This project aims to predict the winning team in college basketball games using various machine learning techniques. The project is part of an IBM course on data science and machine learning.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)


## Overview
In this project, we practice various classification algorithms to predict the winning team in college basketball games. We load a dataset using the Pandas library, apply several classification algorithms, and identify the best model based on accuracy evaluation methods.

## Dataset
The dataset used in this project includes performance data for five seasons of 354 college basketball teams. It contains the following fields:

| Field  | Description |
|--------|-------------|
| TEAM   | The Division I college basketball school |
| CONF   | The Athletic Conference in which the school participates |
| G      | Number of games played |
| W      | Number of games won |
| ADJOE  | Adjusted Offensive Efficiency |
| ADJDE  | Adjusted Defensive Efficiency |
| BARTHAG| Power rating for the team |
| EFG_O  | Effective Field Goal Percentage Offense |
| EFG_D  | Effective Field Goal Percentage Defense |
| ...    | ... (more fields) |

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.7 or later
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `seaborn`

## Installation
To install the necessary libraries, run the following commands:
```bash
pip install pandas numpy matplotlib scikit-learn seaborn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/sruthidusarlapudi/Predicting-the-Winning-College-Basketball-Team.git
```
2. Navigate to the project directory:
```bash
cd Predicting-the-Winning-College-Basketball-Team
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `Project.ipynb` and run the cells to see the analysis and model training process.

## Results
The models are evaluated based on accuracy, precision, recall, and F1 score. The best-performing model is identified and used to make predictions on new data.




