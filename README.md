# Redfin_Data_Analysis
### Table of Contents

1. [Introduction](#introduction)
2. [Libraries and Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Summary of Analysis](#summary)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Introduction <a name="introduction"></a>
This repository uses [Redfin](https://www.redfin.com/) housing market data which covers a range of 10 years to explore the housing market especially compare the numbers from before covid-19 and after covid-19. 
The pandemic had given a big hit to the country's economy, then what the housing market look like before and after the year 2019. Redfin provids data across the country and this project will use python to 
explore the data and then to answer some questions. 

## Libraries and Installation <a name="installation"></a>
There are a list of common libraries used in the projects, numpy, pandas, matplotlib, sklearn, seaborn etc., but 
there should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  
The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

Housing is a big topic in our life. I have been interested in it for a couple of years and I want to use the redfin data to answer the following questions:

1. What are the top 10 metro city with the highest median sale price in each month?
2. what is the housing market looks like before and after 2019 for the top 10 metro city with the highest median sales price?
3. How many house sold in each month nationwide and in the popular cities before and after 2019?


## File Descriptions <a name="files"></a>

There is one jupter notebook with all the code, brief documentation of the code and the run-through result available in the repository to showcase work related to the above questions. 
The Data folder contains the housing market data that downloarded from Redfin data center data used by this analysis.  


## Summary of the Analysis <a name="summary"></a>

1. The top 10 metro area with the highest median price are:
    (Los Angeles, CA metro area, 
    San Francisco, CA metro area, 
    San Jose, CA metro area
    New York, NY metro area 
    .
    .
    .
    .
    .
    )
2. The economy got a hit from the pandemic but seems not apply to the housing market. The outbreak happened on Feburary 2019, the median price has a sesonal dip but afterward, 
   the trend goes up slowly. After 2019, the year over year trend line showing that start from March 2020 the increasing of median price start to have a smaller and smaller number, 
   but it is still increasing until the mid of June and then the median price start to increase rapidly nationwidely. 

3. The pandemic had an short period impact on the housing market, there is a dip from March 2020 to June 2020, the sales prices and the number of house sold both 
   had less increase compare to the previous year, but after June 2020 the numbers starts to increase.

The main findings of the code can also be found at the post available [here](https://medium.com/p/6a6f7fb87edd/edit).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data download from [Redfin](https://www.redfin.com/), a national real estate brokerage.  According to Redfin data center download page, 
the data is open to public and is welcome to be used as personal purposes, we just need cite the source. 
