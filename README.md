# A-B-Testing-of-New-Webpage-for-E-Commerce-Website

## Introduction
The e-commerce company has developed a new web page in order to try and increase the number of users who "convert". My goal is  to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Analysis
Use A/B testing to help the company investigate which page has better conversion rate. <br>
Null hypothesis: P <sub> new </sub> <= P <sub> old </sub> <br>
Alternative hypothesis: P <sub> new </sub> > p <sub> old </sub>
<br>
Use a sample size for each page equal to the ones in ab_data.csv. 
Perform the sampling distribution for the difference in converted between the two pages over 10,000 iterations of calculating an estimate from the null. <br>

By bootstrapping our samples to simulate the sampling distribution based on our null hypothesis, we plot the histogram of differences between the conversion rate of new page and old page. 
We found that 90.98% of simulated samples are greater than the observed statistics (p-value is greater than alpha value, 0.05.), which means the observed value can not be a proof that shows new page brings more conversion rate. 
We can not reject the null hypothesis. 
The conversion rate of new page can not be proved by these observed data that it is greater than the conversion rate of old page.


## Summary
From the result, we found an interaction between page and country is still not a good predictor for conversion rate. 
There is no siginificant relationship between treatment and converted rate, country and coverted rate, intersection of treatment and country and contverted rate. 

We can't see the trend that new page provides better conversion rate, which shows the same conclusion with Part II: <br>
We can not conclude new page is better than old page.
