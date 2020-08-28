# Statistical Model on MakeMyTrip Data
![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Intro.gif)

### Presentation
Watch the [presentation](https://docs.google.com/presentation/d/1bQ9GWi_mMddJiqqoqbrK1IuV-a-9pUTE1zw12B0OKiE/edit?usp=sharing "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://www.youtube.com/watch?v=2S1IZHu8q5M&t=580s "video ")presentation.

Or just continue here.
## Table of Contents
1. [About the Data](#section1)
2. [Problem Statement](#section2)
3. [Applications](#section3)
4. [Attributes of Data](#section4)
5. [Pre-Processing Data](#section5)
6. [Distribution of Data](#section6)
7. [Algorithms Used](#section7)
8. [Comparison of Models](#section8)
9. [ROC Curve Analysis](#section9)
10. [Python Notebook](#section10)
-------

<a id=section1></a>
## 1. About the Data
Given dataset has **100000 observations**. Below is a table showing names of columns and their description.
|Column   		|Description                                                    |
|-------    	|---------                                                    |
|userid     	|Unique id to identify a user                                   |
|signup_date	|Date when the user first signed in with us                     |
|wallet	    	|Amount present in his wallet                                   |
|tier	    	|Current loyality standing                                      |
|txns	    	|total number of transactions                                   |
|sync_tag		|to identify if a customer has synces his contact book or not   |
|operator_name	|Which mobile operator he is using                              |
|state		    |Which state does one's mobile number belongs to                |
|app_status	    |Whether at present customer has mobile app or not              | 
|segment	    |Which type of mobile handset bucket customer lies in           |
|task	        |How many times customer has earned loyality money.             |

<a id=section2></a>
## 2. Problem Statement
- Provide insights about type of customers present with us and their implications on overall data set.
- Who are our top 1 percentile of user. Why are they in this bucket?
- Build a statistical Model to find the probability of repeat transaction by a user and divide them in 10 different buckets of probability with equal user in each bucket.
- What is the probability of users transacting again, who have made single transaction till date?

<a id=section3></a>
## 3. Insights wrt to Years
![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Count%20plot%20for%20year.png)


![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Count%20plot%20for%20year%20wrt%20to%20app%20status.png)


![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Count%20plot%20for%20months.png

<a id=section4></a>
## 4. Insights about Type of Customers 
![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Donut%20Plot%20showing%20the%20proportion%20of%20Tiers.png)


![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Donut%20Plot%20showing%20the%20Proportion%20of%20Sync-tag.png)

<a id=section5></a>
## 5. Top 1 percentile of customers
![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Donut%20Plot%20showing%20the%20Proportion%20of%20Tiers%20of%20Top%201%20Percentile%20Users.png)


![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Donut%20Plot%20showing%20the%20Proportion%20of%20Sync-tag%20of%20Top%201%20Percentile%20Users.png)


![]( https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Images/Count%20of%20app_status%20of%20Top%201%20Percentile%20Users.png)

<a id=section6></a>
## 6. Algorithm used
Logistic regression

<a id=section7></a>
## 7. Python notebook
Find all the codes [here.](https://github.com/somagicc/Statistical-Model-on-MakeMyTrip-Data/blob/master/Statistical_Model_MakeMyTrip_Data.ipynb "here")

Thank you!
