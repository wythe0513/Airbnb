# Seattle Airbnb Open Data


## Datasets

> Data from [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data)
> - data exploreed. 
> - calender.csv : 1393570 rows/4 columns Year 2016 daily daily price data 
> - listings.csv : 3891 rows/91 columns from year 2009 to 2015 various data such as price, rating, review, accomodation, propeerty etc.
> - reviews. csv : 84891 rows/6 colums from Year 2009 to 2015 reviewers cooments

## Summary of Findings

> - Price fluctuation in 2016 is very stable and regular yearly, monthly and weekly. No unexpected or irregular spikes are observed. This trend is reasonably correlated to the availability. The prices of the weekend and holiday season are high and others are not.

> - Trend of price fluctuation from 2005 to 2015 are different from the above. For the earlier part of the period of 2005 to 2015, price fluctuations are very large and look irregular. When this trend is compared to the trend of increase in numbers of hosts, it looks that with the numbers of hosts being increased, the fluctuation of them is getting milder. 

> - Those hosts categorized as 'super host’ got higher ratings and more reviews and non super hosts with less ratings also got more reviews.

> - Linear Regression analysis find out what features are impacts on ratings. As a result, higher weights impacts on rating are types of property, Boat, Couch, Tent are top 3 and then followed by communication and cleanliness review score.


## References

Functions(AllTogether.py) referred from Udacity Data Scientist Nanodegree Course 