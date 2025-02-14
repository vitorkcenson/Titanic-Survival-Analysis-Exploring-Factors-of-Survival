# Titanic Survival Analysis: Exploring Factors of Survival

This repository contains an Exploratory Data Analysis (EDA) notebook analyzing the Titanic passenger dataset. The notebook investigates various factors that influenced survival rates, including age, sex, passenger class, and fare.  Visualizations and interpretations are provided to understand the trends and disparities in survival.

## Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Notebook Overview](#notebook-overview)
* [Key Findings](#key-findings)
* [Dependencies](#dependencies)
* [How to Run the Notebook](#how-to-run-the-notebook)

## Introduction

The sinking of the RMS Titanic is a tragic event in history. This analysis uses the well-known Titanic dataset to explore the factors that contributed to passenger survival.  The goal is to uncover patterns and insights about who was more likely to survive this disaster.

## Dataset

The dataset used in this analysis is the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) dataset from Kaggle. It contains information about passengers on the Titanic, including their age, sex, passenger class, fare, and survival status.

## Notebook Overview

The Jupyter Notebook `titanic.ipynb` performs the following steps:

1. **Data Loading and Cleaning:** Loads the dataset and handles any missing values or inconsistencies.
2. **Exploratory Data Analysis:**  Explores the data through descriptive statistics and visualizations.
3. **Survival Analysis:**  Analyzes survival rates based on various factors:
    * Survival by Sex
    * Survival by Age
    * Survival by Passenger Class
    * Survival by Fare
    * Combined Analysis of Age and Class
    * Combined Analysis of Fare and Class
4. **Visualization and Interpretation:** Creates various plots (bar charts, countplots) to visualize the data and provides interpretations of the findings.

## Key Findings

* **Class and Sex were Crucial:**  The most significant factors influencing survival were passenger class and sex.  First-class females had the highest survival rates, while third-class males had the lowest.
* **"Women and Children First":** The data supports the notion that women and children were prioritized in the lifeboats.
* **Age Matters:** Younger passengers generally had better survival chances than older passengers, although this was strongly influenced by class.
* **Fare and Survival:** Passengers who paid lower fares (majority of the passengers), (and were likely in higher classes) had better survival rates.
* **Family Separation:** The data hints at the tragic separation of families, with many fathers and husbands perishing while their wives and children survived.

## Dependencies

The notebook requires the following Python libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scipy

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
