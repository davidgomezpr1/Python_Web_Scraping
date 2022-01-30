# [Project 7 : Scraping Data from the Amazon Website](https://github.com/davidgomezpr1/Python_Web_Scraping)
![](https://images.unsplash.com/photo-1487058792275-0ad4aaf24ca7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80)

## Motivation

As a Data Analyst and part-time eBay item flipper, I wanted to automate the process of collecting data from Amazon and receiving an email when the items fall below a predetermined price at which I am confident I can make a decent profit.

In this case, the items I am looking for are on-ear bluetooth headphones that meet the following conditions:

- Must have over 20h of battery life.
- Amazon average customer rating of over 4 stars.
- Price must be under €50.
- Headphones must be brand-new or Amazon renewed.
    
I have set a price threshold of €40 so that, with all certainty, I will be able to make at least a 20% profit on the items.


## Overview

- Data was scraped from [Amazon Spain](https://www.amazon.es/).
- Connecting to the websites and pulling in the data.
- Data cleaning of pulled data.
- Creation of a CSV file and appending of cleaned scraped data to it.
- Definition of a function that automates the appending of data to the CSV and sends an email when the items hit a price below the set price.

## Conclusions

- The data was succesfully scraped from the Amazon Website and loaded into the CSV file.
- The function served its purpose and notified me when the price of the item 'JBL Tune500BT' went below the €40 mark.

![Email confirming headphone deal](https://user-images.githubusercontent.com/94221230/149658844-fb47d0a4-18c6-4eb1-b4b2-4d5e0af4f9c2.png)

- Within three days, I was able to sell the item on eBay for €52, making a 30% profit.
