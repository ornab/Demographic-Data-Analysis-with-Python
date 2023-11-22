# Demographic Data Analysis with Python

The International Data Base (IDB, 2022) contains the demographic data of over 200
countries. The demographic data contains the total population by age and sex.

The goal of this project is to descriptively analyse and determine the relationship between
variables using the demographic data ```census2002_2022.csv``` extracted from the
International Data Base (IDB, 2022). This dataset contains life expectancy at birth and
under 5 mortality rates of 227 countries across 5 regions and 21 subregions for 2002 and
2022. **The life expectancy infers the average number of years a group of people who
born in the same year is expected to live if the mortality remains same at all ages in the
future**. On the other hand, **under-5 mortality rates refer to the number
of children who die before age 5 for every 1000 births**.

## Description of the dataset

The dataset ```census2002_2022.csv``` is used in this project and is a small portion of
the International Data Base (IDB, 2022). IDB contains the demographic data of all
the regions and sub-regions recognized by U.S. Census Bureau. The data of this enormous
database is collected through different procedures such as censuses, surveys, and
estimates and projections by the U.S. Census Bureau from 1950s.

The ```census2002_2022.csv``` dataset contains demographic information for 227 countries
across 21 subregions and 5 regions: Asia, Africa, Americas, Europe, and Oceania for
the years 2002 and 2022. The dataset includes life expectancy at birth and under age 5
mortality rates of these countries for males, females, and both sexes. The whole dataset
contains a total of 454 observations and 10 variables with an index X. There are six
continuous variables: $\textsf{Life Expectancy at Birth Both Sexes}$, $\textsf{Life Expectancy at Birth
Males}$, $\textsf{Life Expectancy at Birth Females}$, $\textsf{Under Age 5 Mortality Both Sexes}$, $\textsf{Under Age
5 Mortality Males}$, and $\textsf{Under Age 5 Mortality Females}$, as well as 4 categorical variables:
$\textsf{Country.Area.Name}$, $\textsf{Subregion}$, $\textsf{Region}$, and $\textsf{Year}$. Numerical variables in this report
consist of whole numbers or decimal values defined with 1 or 2 decimal points.

In our given dataset, there is a total of 44 missing values that are replaced by NA. There
exist 36 continuous missing values from six different countries: Libya, Puerto Rico, South
Sudan, Sudan, Syria, and United States for 2002, as well as 8 categorical values for 2002
and 2022. The six countries that are mentioned are not used in the comparison between
the variable values of 2002 and 2022 in task four. Overall, the data quality is better for
analysis in 2022 as only 4 categorical missing values are there compared to 40 missing
values in 2002.

## Project Objectives

In this project, I completed four different tasks by gaining a deeper understanding of the
patterns and connections within the demographic data through statistical techniques.
In task 1, histograms and Maps are used to illustrate the frequency distribution of the values of
each continuous variable. I analysed and compared the life expectancy at birth and
under age 5 mortality rates between males and females, as well as between regions
through boxplots. In task 2, Africa region is used to analyse and determine the 
homogeneity within its subregions for males, females and both sexes, as well as the
heterogeneity between different subregions. Boxplots, measures of spread, and
measures of central tendency are used to complete this task. In task 3, I tried to determine the
bivariate correlation between variables using Pearson correlation coefficients and scatter
plots. The first three tasks consider only the data for 2022. In the final task,
life expectancy at birth and under age 5 mortality rates for males and females, and both
sexes are compared between the years 2002 and 2022 by using scatter plots.
