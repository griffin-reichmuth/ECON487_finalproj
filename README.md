# ECON487 Final Project

## Project details
- In Economics 487 (Data Science for Strateic Pricing), we were tasked with analyzing a messy wholesale purchase data set. My partner Ben Fakler and I investigated the data and used a
- double machine learning algorithm procdure to approximate the price elasticity of two of the highest revenue-grossing products by training a decision tree to predict Quantity and UnitPrice.

- 
##  Methodology info
- Research basis for Double ML procedure in Chernozhukov et al.: https://arxiv.org/pdf/1608.00060.pdf
- A primer for Double Machine Learning can be found here: https://www.linkedin.com/pulse/double-machine-learning-approximately-unbiased-jonas-vetterle



## How to download the Data Needed from our github:
- download our repo at https://github.com/griffin-reichmuth/ECON487_finalpr

## Data
- see excel file "online_retail.xlsx" for the full data set
- "light_data.csv" and "rabbit_data.csv" contain subsets of the data as needed in the RMD file

## Neccessary libraries: 
  - plyr
  - dplyr
  - ggplot2
  - lubridate
  - rpart
  - rpart.plot
  - partykit
  - maptree
 
## How to reproduce our results
- In Rstudio, knit "Final_project_Fakler_Reichmuth.RMD" 


