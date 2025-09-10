![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
# USD/CNY Exchange Rate Forecast

## Project Objective
This project focuses on predicting the direction of the USD/CNY exchange rate (up or down) using various machine learning models. The goal is to explore how macroeconomic and market indicators can help anticipate currency movements.

The models implemented are:
- Neural Network (NN)  
- K-Nearest Neighbors (KNN)  
- Decision Tree and Random Forest  

## Project Structure
- `data/` : contains the dataset `Dataset prediction USDCNY.xlsx`.  
- `src/` : Python scripts implementing the machine learning models.   
- `README.md` : this file, describing the project.  
- `LICENSE` : project license.  

## Dataset
The dataset was compiled manually from public sources, followed by personal calculations, and includes the following variables:
- S&P 500 index  
- SSE Composite index  
- GDP growth differential (USA - China)  
- US interest rate  
- China interest rate  

The dataset is monthly, covering the period from January 2015 to December 2024. Each row corresponds to one month and contains the values of all variables used to predict the USD/CNY exchange rate direction.

This dataset allows for a directional forecast of the USD/CNY exchange rate rather than predicting the exact value.

## Notes
- The project demonstrates data collection, preprocessing, model implementation, and basic evaluation.  
- Results may vary depending on the model choice and parameters.  
- The models aim to predict the direction of the exchange rate, not the exact value.  

## Author
Joshua Lemiere Mac Douglas – Master in Finance 
Contact: Joshuamacdouglas@gmail.com
