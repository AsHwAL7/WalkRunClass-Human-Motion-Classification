# WalkRunClass-Human-Motion-Classification

## Overview
Classifies motion sensor data to detect walking or running using accelerometer and gyroscope data (88,000+ samples).

## Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model to classify whether a person is running or walking based on the given predictor variables.
 

## Attribute Information:

The dataset comprises the readings of motion sensors recorded while users executed typical daily activities. The detailed format is described in the package. The attributes correspond to raw sensor readings. There are a total of 11 attributes.
1.	date
2.	time
3.	username
4.	wrist
5.	activity
6.	acceleration_x
7.	acceleration_y
8.	acceleration_z
9.	gyro_x
10.	gyro_y
11.	gyro_z

## Key Features

-Multiclass classifier using sensor time-series data

-Model comparison: Logistic Regression, Decision Tree, MLP

-Neural network model achieved ~94% accuracy



## Tools & Libraries: Python, scikit-learn, NumPy, Pandas

## Outcome: High-accuracy classifier useful for wearable devices and health tracking
