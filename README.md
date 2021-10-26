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

1. What are the trends of median sales price in each year?
2. What is the year over year variation percentage when comparing different years?
3. How soon can homes be sold and what are the median days that homes on the market?
4. What are the top metro areas in terms of median sales price and the total number of homes sold?


## File Descriptions <a name="files"></a>

There is one jupter notebook with all the code, brief documentation of the code and the run-through result available in the repository to showcase work related to the above questions. 
The Data folder contains the housing market data that downloarded from Redfin data center data used by this analysis and the matrix description that explains most of the terms and columns used in the data.  


## Summary of the Analysis <a name="summary"></a>

1. a)<br>
   The 24 out of 30 top metro areas that stay in the list with the highest median price from 2017-2021 are: <br>
        0      Vineyard Haven, MA metro area <br>
        1       San Francisco, CA metro area <br>
        2          San Rafael, CA metro area <br>
        3            San Jose, CA metro area <br>
        4          Santa Cruz, CA metro area <br>
        5               Heber, UT metro area <br>
        6             Oakland, CA metro area <br>
        7             Anaheim, CA metro area <br>
        8        Breckenridge, CO metro area <br>
        9                Napa, CA metro area <br>
        10        Santa Maria, CA metro area<br>
        11            Salinas, CA metro area<br>
        12            Kahului, HI metro area<br>
        13        Los Angeles, CA metro area<br>
        14              Kapaa, HI metro area<br>
        15             Oxnard, CA metro area<br>
        16           Key West, FL metro area<br>
        17    San Luis Obispo, CA metro area<br>
        18         Santa Rosa, CA metro area<br>
        19          San Diego, CA metro area<br>
        20            Seattle, WA metro area<br>
        21     Urban Honolulu, HI metro area<br>
        22            Boulder, CO metro area<br>
        23           New York, NY metro area<br>

    b)<br>
    The 26 out of 30 top metro areas that stay in the list with the most homes sold from 2017-2021 are: <br>  
        0             Atlanta, GA metro area<br>
        1             Chicago, IL metro area<br>
        2             Houston, TX metro area<br>
        3             Phoenix, AZ metro area<br>
        4          Washington, DC metro area<br>
        5            New York, NY metro area<br>
        6         Los Angeles, CA metro area<br>
        7               Tampa, FL metro area<br>
        8              Dallas, TX metro area<br>
        9         Minneapolis, MN metro area<br>
        10          Riverside, CA metro area<br>
        11             Denver, CO metro area<br>
        12            Seattle, WA metro area<br>
        13            Orlando, FL metro area<br>
        14             Boston, MA metro area<br>
        15          Baltimore, MD metro area<br>
        16          Las Vegas, NV metro area<br>
        17           Portland, OR metro area<br>
        18          Nashville, TN metro area<br>
        19    Fort Lauderdale, FL metro area<br>
        20             Warren, MI metro area<br>
        21    West Palm Beach, FL metro area<br>
        22      New Brunswick, NJ metro area<br>
        23          San Diego, CA metro area<br>
        24       Indianapolis, IN metro area<br>
        25         Fort Worth, TX metro area<br>
    
2. The economy got a hit from the pandemic but the housing market remains strong and steady. The outbreak happened in 2019, the median sales price had a sesonal dip but afterward, the trend goes up. After 2019, the median sales price goes up year after year. There is no slow down during the pandemic. Total number of homes also sold more in 2020 than sold in 2019

3. Homes are also sold fast during and after the pandemic for the metro cities. 42% of homes that went under contract had an accepted offer within first two weeks and that number was 31% a year earlier and 24% in 2019. 31% of metro area homes had an accepted offer within one week and that number was 22% a year ealier and 16% in 2019. 

The main findings of the code can also be found at the post available [here](https://medium.com/p/6a6f7fb87edd/edit).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data download from [Redfin](https://www.redfin.com/), a national real estate brokerage.  According to Redfin data center download page, 
the data is open to public and is welcome to be used as personal purposes, we just need cite the source. 
