# Global Renewal Energy Production Analysis

### Overview

The overview of the project is to examine global renewable energy data to analyze the development of sources like solar, wind, and hydro on a global scale. We aim to identify the countries at the forefront of renewable energy usage and determine which types of technology are most prevalent by analyzing trends across various regions. This analysis will help highlight the progress being made, identify regional differences, and predict future growth. The insights gained will be useful for policymakers, industry leaders, and researchers to support and improve the adoption of renewable energy globally.

### Data Sources

Data set: The Primary dataset used for this analysis is the "global_renewable_energy_production.csv" which contains detail information about the countries renewable energy usage and their prevalent types of technology across various regions.

### Tools

- R

### Data Cleaning/Preperation

In the initial Data preperation, performed the following tasks

- Data Cleaning and Preprocessing: Utilized R for data import and cleaning, to ensure accuracy and consistency.
- Descriptive Statistics: To Compute fundamental statistics to grasp the primary characteristics of the data.
- Data Visualisation: Utilize ggplot2 in R to generate visuals illustrating trends, regional variations, and growth patterns.
- Regression Analysis: To Utilize linear and nonlinear regression models to investigate the impact of various factors on the adoption of renewable energy.
- Analysis of Time Series: To Utilize time series models for examining variations over time and forecasting upcoming patterns.
- Geospatial Analysis: To Generate maps to display the global distribution of renewable energy resources.

### Exploratory Data Analysis

- Which countries are leading in using renewable energy?
- What are the trends in various renewable energy types like solar, wind, and hydro over the last ten years?
- How is renewable energy production related to factors like GDP, population, and energy policies?
- What can we predict about the future growth of renewable energy?

### Data Analysis
---
Title: "Activity"
Output: github_document
---

```{r setup, include=FALSE, warning=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
### Load Nexessary Packages
library(ggplot2) 
- ggplot2 is a tool within R that is utilized for generating data visualizations. Users can create intricate charts such as scatter plots, line graphs, and bar charts easily using a simple yet powerful syntax. We can utilize ggplot2 to generate a scatter plot illustrating the correlation between two variables, and you have the option to modify the colors, shapes, and sizes of the points with ease. This feature makes it a flexible and handy tool for creating visually appealing graphics.
library(dplyr)
- dplyr is a tool in R for handling and transforming data. It has functions that make it easy to do things like filter rows, pick specific columns, group data, and summarize it. For instance, we can use dplyr to select only the rows from a certain year or to calculate the average value of a column. This makes it simple to manage and work with data.
library(reshape2)
- reshape2 is an R tool for changing the structure of data. It helps switch data between wide and long formats, making it easier to analyze or visualize. For example, you can use reshape2 to change a dataset where each row is a different observation into one where each row represents a different variable, which can be useful for certain types of analysis or creating plots.
```

### Resources

- International Renewable Energy Agency (IRENA)
- World Bank Energy Data
- Global Renewable Energy Dataset on Kaggle

### Results/Findings
- Leading Countries: Visualization showing the top countries in renewable energy production.
- Trend Analysis: Line graphs showing the growth of different renewable energy types over the years.
- Correlation Plots: Scatter plots showing the relationship between renewable energy production and economic indicators.
- Forecasts: Time series plots showing predicted future growth of renewable energy.

  
