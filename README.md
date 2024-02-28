# tableau-challenge
### Challenge 18 of UoB Data Analytics bootcamp - Tableau

## Content:
1. [Overview](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#1-overview)
2. [Deployment](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#2-deployment)
3. [Repository](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#3-repository)
4. [Data source](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#4-data-source)

## 1. Overview
The main aim of this assignment was to develop a tableau workbook containing individual visualisations, interactive dashboards and a story, using publicly available data from CitiBike (see [Data Source](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#4-data-source). The workbook should contain one map with all stations and should be aimed at city officials, in order to inform them about temporal changes and current riding patterns. 

## 2. Deployment
The workbook is published on Tableau Public. You can view it [here](https://public.tableau.com/app/profile/catarina.ferreira2233/viz/Citi_Bike_17084488357830/Story2)

<p align="center">
  <img src = "https://github.com/catisf/tableau-challenge/blob/main/dashboard.png" height = "50%" width = "50%">
</p>
<h6 align="center">Fig. 1 - Map visualisation</h6>

## 3. Repository structure
This repository contains:
- [`merge_data.ipynb`](): a jupyter notebook that reads in data from city bike, merges it, and adds columns with day of the week and distance riden.

## 3. Set up and execution
- To access the workbook, you can download the `Citi_Bike` workbook and open it on Tableau Public, or access it a web browser [here](https://public.tableau.com/app/profile/catarina.ferreira2233/viz/Citi_Bike_17084488357830/Story2)
- To use the same data, download the files specified on the Data Source section [below](https://github.com/catisf/tableau-challenge/tree/main?tab=readme-ov-file#4-data-source) and run the jupyter notebook to get the merged data. 

## 4. Data source
- The data used is publicly available on Citi Bike: https://citibikenyc.com/system-data
- The files used pertain to January 2023 and January 2024
