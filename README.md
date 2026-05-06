# Intercity-Travel-Pattern-Analysis-using-Non-negative-Matrix-Factorization

## Background
This project is a small part of my research on mobility pattern analysis using tensor factorization.

## Overview
This project demonstrates how to extract mobility patterns from spatiotemporal data using Non-negative Matrix Factorization (NMF).

## Data
Traveler data between Japan's 47 prefectures in 2019

## Result
The W matrix shows: Number of people traveling for each travel behavior over the time series.
The H matrix shows: The ratio of people traveling for each OD pair and each travel behavior.

Combining the information of matrix W and H from the NMF result, we achieved three travel behaviors:
+ Component 1: Business
+ Component 2: Visiting relatives and friends
+ Component 3: Leisure/Sightseeing
