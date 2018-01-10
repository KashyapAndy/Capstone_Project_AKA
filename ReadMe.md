# EXECUTIVE SUMMARY

The goal of the project was to understand the factors that affect the price of whisky. The whisky market is steadily growing in the US and the market is currently flooded with whisky from tons of new distilleries and craft stills. 

Using webscraping (with approval - see below), we were able to scrape the entire whisky collection from The Whisky Exchange. The data was saved and cleaned using deductive imputations to account for null values. The data set was then analyzed using Natural Language processing to create features based off flavors, age, vintage and other characteristics of a whisky.

After fitting logistic regression model along and optimizing performance using RandomForestClassifiers, we were able to predict the class of whisky with an accuracy of 0.7. we were able to conclude that the age, vintage, flavors, description, distillery, country all play a part in deciding the price of a whisky.

Armed with the information from the model, we are now better suited to purchase whisky and know the value we are getting.

## Project Background

As a collector & a big fan of single malt scotch whisky, I wanted to work on a project that combined my hobbies and data science skills. As a data scientist, I have an interest in building models and using NLP to classify text and applying those skills to business problems. 

So, I approached <a href = 'www.thewhiskyexchange.com'> The Whisky Exchange (TWE) </a> so that I could create models and understand the factors determining the price of whisky.

## Project Overview

The data was scraped from TWE using BeautifulSoup, the EDA was done and Logistic Regression, RandomForestClassification models were fit on the cleaned up data. 

A typical whisky page is: https://www.thewhiskyexchange.com/p/41438/highland-park-the-dark-17-year-old

Information regarding price, description, facts, customer reviews, total reviews and other information was scraped and was then cleaned analyzed using BeautifulSoup.

## Project Workflow

Scope --> Scraping Data --> EDA --> Deductive Imputation --> Model Building --> Model Optimization --> Conclusions --> Handoff

## The Data:

All data files is available on request.

The data is prorpietary to The WhiskyExchange. No unauthorized downloads allowed.

## License

It is important to note that this project was done with the explicit approval of The Whisky Exchange (TWE) (www.thewhiskyexchange.com). The terms of services of TWE are as follows:

````````
No photography, imagery, text, source code or any other material shown on TWE website (thewhiskyexchange.com) may be used in any circumstances for commercial purposes, nor may any of our material herein be altered, cropped, transformed, built upon, or in any other way changed or reproduced, whether from our own websites or copied from third party websites in breach of this condition themselves or otherwise redistributed without our prior written permission.

You may not engage in any price scraping or price harvesting in respect of products on 'the site' without our prior written consent.

````````

