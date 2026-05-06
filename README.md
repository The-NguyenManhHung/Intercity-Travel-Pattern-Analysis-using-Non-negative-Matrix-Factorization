# Intercity-Travel-Pattern-Analysis-using-Non-negative-Matrix-Factorization

## Background
This project is a part of my research on mobility pattern analysis in my Master's course and was converted from my MATLAB code to Python.

## Overview
This project demonstrates how to extract mobility patterns from spatiotemporal data using Non-negative Matrix Factorization (NMF).

## Data
Traveler data between Japan's 47 prefectures in 2019.

## Result
The W matrix shows: Number of people traveling for each travel behavior over the time series.
The H matrix shows: The ratio of people traveling for each OD pair and each travel behavior.

Combining the information of matrix W and H from the NMF result, we achieved three travel behaviors:
+ Component 1: Business
![Component 1](outputs/W_mat_component_1.png)
![Component 1](outputs/H_mat_component_1.png)

+ Component 2: Visiting relatives and friends
+ Component 3: Leisure/Sightseeing
