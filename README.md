# Life Expectancy Regression Using ANN

# Overview

- An Artificial Neural Network project dedicated to predict Life expectancy of nations based on provided data from The Global Health Observatory (GHO) data repository under World Health Organization (WHO) 

- The project highlightsthe significance of Data Cleaning (Preprocessing) ,Data Exploration (Descriptive Statistics) , and employs professional visualizations to enhance data understanding.

# Features of dataset

|Feature | Description
|------|------------
|**Country** | countries has been collected from the same WHO data repository website 
|**Year**|year 2013-2000
|**Status**|Status of country **Developing** or **Developed**
|**Life expectancy**|Life Expectancy in age **our target**
|**Adult Mortality**|Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)
|**infant deaths**|Number of Infant Deaths per 1000 population
|**Alcohol**|Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)
|**percentage expenditure**|Expenditure on health as a percentage of Gross Domestic Product per capita(%)
|**Hepatitis B**|Hepatitis B (HepB) immunization coverage among 1-year-olds (%)
|**Measles**|Measles - number of reported cases per 1000 population
|**BMI**|Average Body Mass Index of entire population
|**under-five deaths**|Number of under-five deaths per 1000 population
|**Polio**|Polio (Pol3) immunization coverage among 1-year-olds (%)
|**Total expenditure**|General government expenditure on health as a percentage of total government expenditure (%)
|**Diphtheria**|Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
|**HIV/AIDS**|Deaths per 1 000 live births HIV/AIDS (0-4 years)
|**GDP**|Gross Domestic Product per capita (in USD)
|**Population**|Population of the country
|**thinness  1-19 years**|Prevalence of thinness among children and adolescents for Age 10 to 19 (% )
|**thinness 5-9 years**|Prevalence of thinness among children for Age 5 to 9(%)
|**Income composition of resources**|Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
|**Schooling**|Number of years of Schooling(years)

# Dataset

- Source : [Life Expectancy (WHO)](https://www.google.com](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- Preprocessing
- - Handling Missing Values
  - Handling Outliers
  - Handling Categorical Features
  - Data Scaling
 
# Model Architecture

- ANN sequential model with input layers of 64 neurons and activation function = 'relu' ,two hidden layers of 64 neurons and activation function = 'relu' and output layer of 1 neuron with activation function ='linear'
- Optimizer used 'Adam'
- Loss Function used 'mean_squared_error'
