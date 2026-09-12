# Lab 6: Statistical Analysis of Palmer Penguins

## Overview
This repository contains the R programming analysis for "Lab Problem Statement 6: Statistical Analysis of Physical Characteristics of Palmer Penguins"[cite: 1]. The project investigates whether physical characteristics, such as body mass and flipper length, differ significantly across penguin species and sex[cite: 1]. 

## Topics Covered
* Descriptive Statistics[cite: 1]
* Hypothesis Testing (Two-sample t-test)[cite: 1]
* One-Way and Two-Way ANOVA[cite: 1]
* Post-hoc Analysis (Tukey HSD)[cite: 1]
* Non-Parametric Tests (Kruskal-Wallis)[cite: 1]
* Data Visualization (Histograms, Boxplots, Density Plots, QQ-plots)[cite: 1]

## Dataset
**Palmer Penguins Dataset** (UCI Machine Learning Repository)[cite: 1]
The dataset contains observations of 344 penguins belonging to three species (Adélie, Chinstrap, Gentoo)[cite: 1]. The primary variables analyzed include:
* `species`: Penguin species[cite: 1]
* `sex`: Sex of the penguin[cite: 1]
* `body_mass_g`: Body mass in grams[cite: 1]
* `flipper_length_mm`: Flipper length in millimetres[cite: 1]

## Files in this Repository
* `Palmer_Penguins_Analysis.ipynb` (or `.R` file): The main Google Colab notebook/script containing the complete R code and statistical analysis.
* `Lab_6_Submission.pdf`: The exported PDF report containing code, visualizations, and statistical interpretations.

## How to Run
The analysis is written in R. If running locally, ensure you have R installed along with the following packages:
```R
install.packages(c("palmerpenguins", "dplyr", "ggplot2", "e1071", "car", "effsize"))
