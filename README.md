# Airbnb data analysis with python

This repository contains python code for data wrangling and visualisations of [Airbnb data](http://insideairbnb.com/get-the-data.html). This project aims to understand what factors might play a crucial role to make a certain Airbnb listing popular over others.

## Requirements
- **Python 3.7+**

- **Numpy** (`pip install numpy`)

- **Pandas** (`pip install pandas`)

- **MatplotLib** (`pip install matplotlib`)

- **Seaborn** (`pip install seaborn`)

If  you are using **anaconda virtual environment**, you can install the above packages by running `conda install package-name`.

## List of files

- _**listings.csv**_ : This file contains summarized informations and features of various Airbnb listings in Boston, US.

- _**reviews.csv**_ : This file contains detailed reviews of various listings in Boston along with the reviewer id, name and date of review.

- _**calender.csv**_ : This file has detailed calender data for listings along with their ids in Boston.

- _**airbnb_data_analysis.ipynb**_ : This is a jupyter notebook containing python code for data wrangling and visualisations based on Airbnb Boston listing data.

## A look into the code

![my image](screenshot.png)

The analysis focuses mainly on the following questions :

- How much does location of a listing contribute to it's popularity?
- What causes a property to cost more than others?
- Does background of a host have an impact on listings?
- What roles do booking policies play?
- What can we conclude from the 'age' of a listing?


The .ipynb file holds data cleaning and visualisation codes that try to find answers to the above questions by providing deeper insight into the data. This notebook comes with a detailed explanation of different data cleaning methods used in the analysis and also highlights the important findings.

## External link

See my article on this analysis on [**Medium**]().
