# Projects-based-on-R-

## About Dataset 
 1) The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries
 2)The data-sets are made available to public for the purpose of health data analysis. 
The data-set related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website.
 3) Among all categories of health-related factors only those critical factors were chosen which are more representative. 
 4) It has been observed that in the past 15 years , there has been a huge development in health sector resulting in improvement of human mortality rates especially in the developing nations in comparison to the past 30 years.

## Data Cleaning 

### 1) MISSING VALUE DETECTION
      To find missing values sum(is.na()) provides total number of missing values.
       In our data we got 2563 NA values out of total 2938 observations.
### 2) DEALING WITH MISSING VALUES 
       Dropping this value will result in loss of  50% of data 
       Hence replacing them with median found to be appropriate as median is most 
       centralized value.

 ## Data Visualization 
 
 ![image](https://user-images.githubusercontent.com/96919264/147963916-ab2b7557-79e5-42a9-bd20-4a4b1a299740.png)

 
 
