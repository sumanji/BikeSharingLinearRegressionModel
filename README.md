# Project Name
> Bike Sharing Linear Regression Model :
    A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


As a ML engineer we have created a model which can analyze the feature which can be helpful for the organization to concentrate  on the important factor  for the growth of the business.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendation](#Recommendation)
* [Acknowledgements](#acknowledgements)


## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- With this case study as a Ml emngineer , I analyzed the dataset containing information about  bike sharing features  using EDA to    understand how few attributes can give an insight for growing the business of the bike sharing.
- We are given with  data set  which contains  information for all the features  during time period 2018 and 2019. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Observation from our Training set :
        R2 value is 0.849
        Adjusted R2 value is 0.844
        Prob (F-statistic): 1.20e-190(very low means our fit is not by luck)
        Durbin-Watson: 2.030
2. After our model is successfully created we have predicted the target variable and testing using r2 score which is arround 0.825  which is very close to our training model R2 value i.e 0.849.Hence we can say that our model is good to predict.

3.	From the box plot drawn between season and cnt column we can see that on an average during  fall season around 5700 user has used boom      bikes followed by Summer season with 5500 user.
4.Lowest use of boombike is done during spring season
5. We can see that most use of the boombike comes in  between the month of may to October.Least use of boombike is in the month of Jan.
6. On an average we see similar use of the boombike throughout the week.
7. Maximum uses of the boombike is used during clear weather and then in cloudy season and very less use during rainy season.


## Recommendation
1. After carefull observation we see that season has good amt of impact on the usage of the bike ,so we should provide more bikes for usage during  fall season.
2. we also see that negative correlation of -0.09 from humidity ,hence it is inversily proportionate to cnt variable.
3. we alsoe see that temp has huge impact on the usage of the bike.





## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.23.5
- matplotlib - version 3.7.0
- seaborn - version 0.12.2
- scikit-learn - version 1.2.1
- statsmodels - version 0.13.5



## Acknowledgements
- This project has helped to  develop a basic understanding and creation of linear regression model and analysing the residuals and finally predicting the target variable.
- Geeks for Geeks and official documentation of python libraries has helped a lot to understand the charts and best utilization of it.



## Contact
Created by sumanji.aec@gmail.com  - feel free to contact me!
