#  Covid19-Analysis-and-Visualization-Project:india:

## Cover Photo
![](https://i.imgur.com/CWUoTet.jpg)

## Table of Content
   * [Overview](#Overview)
   * [Motivation](#Motivation)
   * [Technical Aspect](#Technical-Aspect)
   * [Installation](#Installation)
   * [Report Analysis](#Report-Analysis)
   * [Technologies Used](#Technologies-Used)



## Overview
This is an Interactive Data Visualization for exploring Corona Virus Spread in India. Main focus of this project is to show case COVID data analysis from various aspect like gender, state, district, type of transmission etc.

## Motivation
COVID-19 may not be fatal but it spreads faster than other diseases, like common cold. Every virus has Basic Reproduction number (R0) which implies how many people will get the disease from the infected person. As per inital reseach work R0 of COVID-19 is 2.7.
Currently the goal of all scientists around the world is to "Flatten the Curve". COVID-19 currently has exponential growth rate around the world. Flattening the Curve typically implies even if the number of Confirmed Cases are increasing but the distribution of those cases should be over longer timestamp. In simple term, if COVID-19 is going to infect 100k people, then it should be infected within 5-6 months, not on a month.

## Technical Aspect
This project is divided into three major parts:
1. __Data Collection__: Get real time case data from [Covid-19 India Tracker Data](https://api.covid19india.org/csv/)
2. __Data Preprocessing__: Preprocess data in required format and strore in csv file
3. __Data Visualization__: Analyzing cases from various aspect by using matplotlib and plotly. 
    - Bar Chart
    - Pie Chart
    - Histogram
    - TreeMap
    - Scatter Plot
    - Line Graph

## Installation
This project is built in Python 3.6.9. If you don't have python installed, you can find it [here](https://www.python.org/downloads/). Make sure you are using latest version of pip package. Create a separate virtual environment:
```bash
conda create -n covid19_visualization python=3.6
```
Then activate conda environment:
```bash
conda activate covid19_visualization
```
After cloning this repository run the below command to install required libraries.
```bash
pip install -r requirements.txt
```
To collect data run api.pynb file.
For analysis purpose run COVID_19_Data_Analysis.ipynb

## Report Analysis
### Patient Information
![](https://i.imgur.com/LL9p5fg.png) ![](https://i.imgur.com/dKGQH1h.png) 
![](https://i.imgur.com/A07ISQW.png)
![](https://i.imgur.com/GSRl5Nq.png)
![](https://i.imgur.com/anUN6zF.png)
![](https://i.imgur.com/2H5GI4t.png)

__Comment:__
    - Male persons are affected more comparative to Female. Male and Female ratio is 2:1.
    - Adults(20-55) are infected more.
    - Local transmission is the main factor of spreading this virus.



## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)![](https://forthebadge.com/images/badges/uses-git.svg)

[<img target="_blank" src="https://i.imgur.com/vIZmm5z.png" width=150>](https://pandas.pydata.org/) [<img target="_blank" src="https://i.imgur.com/1iCVgf8.png" width=150>](https://plotly.com/python/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg">](https://matplotlib.org/)


