# Multiple Linear Regression Model for the Heating Rate of a Battery in an Electric Vehicle 
This project is a part of the AAI-500 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).   
-- Project Status: Completed
## Data Source
Dataset can be accessed at: https://ieee-dataport.org/open-access/battery-and-heating-data-real-driving-cycles  
## Project Intro/Objective   
The main purpose of this project is to generate a model from a dataset to describe the battery heating rate in an electric vehicle given a specific scenario. The large scale at which lithium-ion batteries are used in EVs pose a risk for significant temperature increase during high power extraction. An accurate model of the battery heating rate is an essential part of developing a thermal management system which can be used to predict unsafe scenarios.      
## Partners, Contributors  
- Patricia Enrique: penrique@sandeigo.edu 
- Frank Ivey: fivey@sandiego.edu
## Methods Used  
Multiple Linear Regression   
## Technologies  
Python  
## Project Description  
The dataset used is from the IEEE DataPort which contains 72 trips taken using an EV. Each trip records information about the environment, vehicle, battery, and heating circuit. The features in the dataset include date, route, weather condition, battery start and end temperature (°C), battery start and end state of charge (SOC) (%), ambient temperature (°C), target cabin temperature (°C), distance driven (km), duration of the trip (min), fan level, and additional notes.  
The analysis is exploring which features affect the rate at which the battery temperature increases and if a maultivariate linear regression model can be generated to represent the relationship between the explanatory variables and the response variable. 
