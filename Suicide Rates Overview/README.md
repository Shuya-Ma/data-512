# 512 Final Project

## Abstract

Suicide has been a global phenomenon and a serious public health issue. This project aims at analyzing the distributions of suicide rates across countries, gender groups, and age groups, as well as to figure out if there are any factors correlated with the suicide rate.
The main purpose of this project is to draw public attention to this issue. Based on exploratory data analysis of the dataset suicide rates overview 1985 to 2016 from Kaggle, we can observe that there are age and gender disparities in suicide rate globally as well as among US population -- suicide rate of male is three times higher than of female and suicide rate increases with age.
Based on the correlation matrix, we can conclude that suicide is correlated with gender, age, and HDI (Human Development Index). Also, it is glad to see a decline in the suicide rate of the global population, however, in the united states, there is an increase in the past 15 to 20 years, which deserves our great attention.

## Data

The dataset used in this project is suicide rates overview 1985 to 2016 from Kaggle, which can be downloaded [here](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016) or can be found in the [data](https://github.com/Shuya-Ma/data-512/tree/main/Suicide%20Rates%20Overview/data) folder. The dataset contains incomplete data for year 2016 , so I exclude that year from my study.

The descriptions of column variables are listed below:
- Country 
- Year : 1985 - 2016
- sex : Male/Female
- age : age group (5-14, 15-24, 25-34, 35-54, 55-74, 75+)
- suicides_no : Number of suicides
- population : Number of all living people
- suicides/100k pop : suicide rate (per 100k population)
- country-year : country-year composite key
- HDI for year : Human development index of each country at given year
- gdp_for_year : GDP of each country at given year
- gdp_per_capita : GDP per capita of each country at given year

## Result
All the output plots can be found in the [plot](https://github.com/Shuya-Ma/data-512/tree/main/Suicide%20Rates%20Overview/plot) folder.


## License
This project is licensed under [MIT License](https://github.com/Shuya-Ma/data-512/blob/main/Suicide%20Rates%20Overview/LICENSE)