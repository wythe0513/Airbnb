# Seattle Airbnb Open Data


## Datasets

> Data from [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data)
> - data exploreed. 
> - calender.csv : 1393570 rows/4 columns Year 2016 daily daily price data 
> - listings.csv : 3891 rows/91 columns from year 2009 to 2015 various data such as price, rating, review, accomodation, propeerty etc.
> - reviews. csv : 84891 rows/6 colums from Year 2009 to 2015 reviewers cooments

## Summary of Findings

> Price fluctuation in 2016 is very stable and regular throughout yearly, monthly and weekly. No unexpected or irregular spikes are observed. This trend is well correlated to the availability.  The weekend and holiday　season are high and others are not. It seems to me that Seattle is a destination of tour or resort. 

![daily_ave](/Users/wythe/Desktop/airbnb/daily_ave.png)



> Trend of price fluctuation from 2005 to 2015 are different from the above. For the earlier part of the period of 2005 to 2015, price fluctuations are very large and look irregular. When this trend is compared to the trend of increase in numbers of hosts, it looks that with the numbers of hosts being increased, the fluctuation of them is getting milder. In 2016, not only the fluctuation of the price is stable but also it looks to move regularly and expectedly as mentioned earlier. A hypothesis comes up in my mind that the rapid growth of Airbnb share house business in Seattle has now reached the saturation stage with the market  supply-demand has been well balanced.

> It is clear that the hosts categorized as ‘super hose’ got high ratings. I made Linear Regression analysis to find out what are impacts on ratings. As a result, higher weights impacts on rating are types of accommodation. boat house is the No.1 and etc.
This, together with the above, makes me feel that in order to grow further beyond, it is necessary to find new special experiences particularly in Seattle besides boats. 

> In addition, looking at the numbers of comments, those are negatively correlated to the rating. It is similar to the saying, “no news. good news”.

## References

> Function for Linear Regression refered to Udacity Data Science Nanodigree Course 