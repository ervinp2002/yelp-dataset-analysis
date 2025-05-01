# Investigating Factors Contributing to High Star Ratings on Yelp

Author: Ervin Pangilinan

COSC 526: Data Mining & Analytics - Spring 2025

## Description

This is an investigation into factors that contribute to high star ratings 
in the Yelp Dataset. This project aims to analyze the Yelp dataset to 
identify key factors that influence the star ratings along with exploring 
geographic hotspots. The analysis includes data cleaning, exploratory data 
analysis (EDA), and machine learning models for regression and clustering 
to predict star ratings based on various features and perform geo-spatial 
analysis.

## Research Questions

Here are the questions that this Jupyter notebook will investigate:

1. What are the key factors that contribute to high star ratings for 
restaurants in the Yelp dataset?
2. Can we predict star ratings based on various features using machine 
learning models?
3. What are the geographic hotspots for various restaurant types?

## Dataset

The Open Yelp Dataset can be found at the following link: https://business.yelp.com/data/resources/open-dataset/

Since the dataset itself is too large to include in this repo, a link
to download the data has been provided. In the download section, select
*Download JSON*. You will then have to extract the zipped folder and move
the .json files to this repo.

## Installation

This notebook was built with Python 3.12.7 conda environment from the
most recent version of Anaconda at the time of this writing. However,
other third party libraries that are used include:

- Pandas
- Sci-Kit Learn
- NumPy
- Matplotlib
- Seaborn
- GeoPandas
- Shapely
- Cartopy

A *requirements.txt* file is included to install all necessary third-party
libraries if you are not using conda for your Python environment. However,
if you are using conda, the first cell in the notebook can be executed
to install these libraries to your conda environment without the use of
the *requirements.txt* file.

## Usage

Once all of the .json files have been downloaded to this repo, then you can press `Run All` to execute everything.

## Contact

The author can be contacted at: `epangili@vols.utk.edu`
