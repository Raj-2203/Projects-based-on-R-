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
 
![image](https://user-images.githubusercontent.com/96919264/147964022-c5f5e767-c609-419a-ad85-98c4c12c8b8f.png)
#### _Japan is the country with the highest Life expectancy value followed by Sweden and Sierra Leone has the lowest Life expectancy value

![image](https://user-images.githubusercontent.com/96919264/147964231-053585ff-662d-4db8-9600-9bce4195cab5.png)

#### _The life expectancy value in case of developing countries is low whereas in case of Developed countries the life expectancy value is comparatively high.

### Effect On Life Expectancy 

#### 1)
![image](https://user-images.githubusercontent.com/96919264/147964363-57e8cb2e-8a56-41d0-82c8-9c76ef5e2f4d.png)
#### _here is a slight decrease in the life expectancy value in case of developed countries whereas in case of Developed countries the life expectancy value is gradually rising which means that developing countries are taking measures for setting up vaccine of hepatitis B

#### 2) 
![image](https://user-images.githubusercontent.com/96919264/147964487-89452b2f-1fe4-4ce7-bdd2-313bc42a0bff.png)
#### _In case of Measles, according to the graph the developed countries seems to have vaccines available to tackle measles whereas developing countries life expectancy values is decreasing day by day maybe because of lack of resources to handle measles





 
