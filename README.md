# covid-analysis

## Demo
**Tableau:** https://public.tableau.com/app/profile/vikram.nayyar/viz/covid-analysis-march2022/Dashboard1

## Introduction
An analysis is done on Corona virus cases (https://ourworldindata.org/covid-deaths). Extracting key informations, a dashboard was developed using **Tableau**.     

## Dataset
The dataset comprises of actual information obtained from https://www.dineout.co.in/. This consists of diverse restaurants from **12** states and **22** major cities and numerous localities. 

The dataset was acquired using **web scraping** with BeautifulSoup. It has **7533** rows with **8** features.   

## Problem Statement
The coronavirus continues propagating around the world at an astonishing rate. With numerous unreported cases, the world reported over 300 million cases.
Many countries like Australia are in a panic situation.   

## Goal
This work was performed as a personal project. The motivation was to obtain an analysis on Covid cases around the world. 

## System Environment
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/)     [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://numpy.org/)     [<img target="_blank" src="https://funthon.files.wordpress.com/2017/05/bs.png?w=772" width=200>](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)     [<img target="_blank" src="https://docs.python-requests.org/en/v1.1.0/_static/requests-sidebar.png" width=100>](https://docs.python-requests.org/en/latest/)     
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/Plotly-logo-01-square.png/1200px-Plotly-logo-01-square.png" width=200>](https://plotly.com/)     [<img target="_blank" src="https://miro.medium.com/max/1400/1*QxfkTc6W2v2jpQBo-HBw0g.jpeg" width=300>](https://plotly.com/dash/)                       


## Directory Structure

```bash
├── data                                           # Data files    
|  ├── all_restnt_details.json                     # Details of all restaurants (Web scraping output) 
|  ├── all_restnt_urls.csv                         # Links of all Dinoeut restaurants in India 
|  ├── clean_data.csv                              # Cleaned dataset 
|  ├── raw_set.csv                                 # Raw dataset (Web scraping output)
├── notebooks                                      # Main project files
|  ├── data_analysis.ipynb                         # Data analysis notebook
|  ├── web_scraping.ipynb                          # Web scraping notebook
├── visualizations                                 # Analysis visualizations
|  ├── 01-rating-distribution.png                  # Restaurant rating distribution 
|  ├── 02-cost-dstribution.png                     # Restaurant cost distribution
|  ├── 03-votes-distribution.png                   # Restaurant votes distribution
|  ├── 04-restnts-across-states.png                # Restaurant distribution across Indian states 
|  ├── 05-restnts-across-cities.png                # Restaurant distribution across Indian cities
|  ├── 06-rating-comparison-of-states.png          # Rating comparison of states
|  ├── 07-rating-comparison-of-cities.png          # Rating comparison of cities
|  ├── 08-cost-across-states.png                   # Restaurant cost distribution across states
|  ├── 09-cost-across-cities.png                   # Restaurant cost distribution across cities
|  ├── 10-votes-across-states.png                  # Restaurant votes distribution across states
|  ├── 11-votes-across-cities.png                  # Restaurant votes distribution across cities
|  ├── 12-comprehensive-comparison-of-states.png   # Performance comparison of all states   
|  ├── 13-top-cuisines-distribution.png            # Confusion matrix of XGBClassifier  
|  ├── 14-top-cuisines-comparison.png              # Top cuisines of respective states
|  ├── 15-favorite-cuisines-in-India.png           # Favourite cuisines in India
|  ├── 16-top-localities-Maharashtra.png           # Top localities in Maharashtra
|  ├── 17-top-localities-Delhi.png                 # Top localities in Delhi
|  ├── 18-top-localities-Karnataka.png             # Top localities in Karnataka
├── LICENSE                                        # License
├── README.md                                      # Repository description
├── requirements.txt                               # Required libraries

```
