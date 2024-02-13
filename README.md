# NFL Big Data Bowl 2023 Repository

Welcome to the repository for the NFL Big Data Bowl 2023, where we delve into the intricacies of tackling performance, particularly focusing on yards after contact in pass plays. This project is part of the Kaggle competition, aiming to extract valuable insights from the extensive NFL tracking data.

## Overview

The primary objective of this project is to analyze and model the factors influencing yards gained after contact during pass plays. Leveraging the rich dataset provided by the NFL, we explore various features such as player speeds, distances, and physical attributes to gain a comprehensive understanding of tackling dynamics.

## Key Features

- **Data Exploration:** We started by exploring the available NFL tracking data to identify key variables and patterns that could influence yards after contact.
  
- **Data Preprocessing:** Significant efforts were dedicated to cleaning and preparing the dataset. We categorized plays, identified key players, and engineered relevant features to facilitate meaningful analysis.

- **Modeling:** We experimented with various regression models, including linear regression, Lasso regression, and Random Forest regression, to predict yards after contact. These models were assessed based on metrics like mean squared error and R-squared.

- **Feature Importance:** Utilizing a number of classification models, we attempted to predict wether or not a tackle would be broken on a given play

## Project Structure

- **Notebooks:** The repository includes Jupyter notebooks detailing the step-by-step process of data exploration, preprocessing, modeling, and feature analysis.

- **Data:** The 'data' directory contains the raw and processed datasets used throughout the project.

- **Animation:** This section houses the function for animating plays from the tracking data
