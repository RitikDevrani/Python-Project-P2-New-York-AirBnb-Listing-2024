# New York Airbnb Listing Analysis
## Project Overview

This project performs Exploratory Data Analysis (EDA) on the New York Airbnb Listings dataset to understand pricing patterns, availability, and neighborhood trends.

The goal of this analysis is to discover insights about Airbnb listings in New York City, such as which neighborhoods have the highest number of listings, pricing distribution across different areas, and room type preferences.

## Objectives

The main objectives of this project are:

• Analyze Airbnb listing data to understand pricing trends

• Identify neighborhoods with the highest number of listings

• Study the distribution of different room types

• Explore availability patterns of listings

• Generate insights that can help hosts and travelers understand the market

## Dataset Description

The dataset contains information about Airbnb listings in New York City, including:

• Listing ID

• Listing Name

• Host ID

• Host Name

• Neighborhood Group

• Neighborhood

• Latitude

• Longitude

• Room Type

• Price

• Minimum Nights

• Number of Reviews

• Reviews per Month

• Availability (365 days)

## Technologies Used

The following tools and libraries were used in this project:

• Python

• Pandas

• NumPy

• Matplotlib

• Seaborn

• Jupyter Notebook

## Project Workflow
### 1. Data Import

Load the dataset and required libraries.

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

df = pd.read_csv("AB_NYC_2019.csv")

### 2. Data Cleaning

Data preprocessing steps include:

• Handling missing values

• Removing unnecessary columns

• Checking duplicate records

• Converting data types

Example:

df.dropna(inplace=True)

### 3. Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset and identify patterns such as:

• Price distribution of listings

• Neighborhood wise listing distribution

• Room type popularity

• Availability trends

• Relationship between price and location

### 4. Data Visualization

Various charts and graphs were created to visualize insights from the dataset.

Examples include:

• Price distribution charts

• Neighborhood group comparison

• Room type distribution

• Availability analysis

Example visualization:

sns.countplot(x="room_type", data=df)

## Key Insights

Some important insights obtained from the analysis include:

• Manhattan has the highest number of Airbnb listings

• Entire home/apartment is the most popular room type

• Prices vary significantly across different neighborhoods

• Some listings have high availability throughout the year while others are limited

## Project Structure
Newyork-Airbnb-Listing-Analysis

│

├── Newyork_AirBnb_Listing_Analysis.ipynb

├── AB_NYC_2019.csv

├── README.md

## How to Run the Project
1 Clone the repository

git clone https://RitikDevrani/Newyork_AirBnb_Listing_Analysis.git

2 Navigate to the project folder

cd Newyork-Airbnb-Listing-Analysis

3 Install required libraries

pip install pandas numpy matplotlib seaborn

4 Run the notebook

jupyter notebook

Open Newyork_AirBnb_Listing_Analysis.ipynb and run the cells.

## Future Improvements

Possible improvements for this project include:

• Building machine learning models to predict Airbnb prices

• Creating an interactive dashboard using Power BI or Tableau

• Adding geographical visualization using maps

## Author

Ritik Devrani

Diploma in Computer Science

BCA (IGNOU)
