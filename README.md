# Bike Sharing MLR Assignment
This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


### Business Goal:
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 



## Conclusions
### **r2 Value = 0.82 
### **Adjusted r2 = 0.816 

### Model Equation : 
**cnt = 0.3087 + 0.2406 * yr - 0.0808 * holiday + 0.3546 * temp - 0.1211 * windspeed - 0.1456 * spring + 0.0594 * March + 0.0716 * October + 0.0766 * September - 0.0439 * Tuesday - 0.2949 * Light_Snow_Or_Rain - 0.0688 * Mist_Or_Cloudy**

### Top Variables Contributing
1. temp - Positive Correlation
2. yr - Positive Correlation
3. Light_Snow_Or_Rain - Negative Correlation




## Technologies Used
- pandas
- numpy
- seaborn
- matplotlib
- statsmodel
- sklearn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

### **r2 Value = 0.82 
### **Adjusted r2 = 0.816 

### Model Equation : 
**cnt = 0.3087 + 0.2406 * yr - 0.0808 * holiday + 0.3546 * temp - 0.1211 * windspeed - 0.1456 * spring + 0.0594 * March + 0.0716 * October + 0.0766 * September - 0.0439 * Tuesday - 0.2949 * Light_Snow_Or_Rain - 0.0688 * Mist_Or_Cloudy**

### Top Variables Contributing
1. temp - Positive Correlation
2. yr - Positive Correlation
3. Light_Snow_Or_Rain - Negative Correlation


## Contact
Created by [@prabhats97](https://github.com/prabhats97) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->