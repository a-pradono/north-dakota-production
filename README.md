<p align="center">
  <img width="800" height="300" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/ND-sign.jpg">
</p>

## Table of Contents

- [I. Introduction](#i-introduction)
- [II. Data and Methodology](#ii-data-and-methodology)
- [III. Results](#iii-results)
- [IV. Conclusions](#iv-conclusions)

## I. Introduction
Data collection is an essential part of whether you are performing research in an industry or academic project. In general, data collection can be difficult and time-consuming, or at least based on my personal experience. When I was doing research, I have gathered data from website reports and stored it manually in an excel spreadsheet. However, not all of those reports came with xls format. The journey began when the data of multiple pages came with pdf formats and manual-typing was performed in my spreadsheet table. This process could take days or weeks or even months depending on your datasets. Therefore, the objective of this project was to reduce time spent on data collection processes by automatically scraping data from the website and transforming pdf into csv formats for further data analytics purposes in North Dakota.

## II. Data and Methodology
This project is built off using the North Dakota state government official portal which can be found [here](https://www.dmr.nd.gov/oilgas/stats/statisticsvw.asp). The datasets came from two separate data frames, which are oil production and gas production counties. These data consist of 840 rows x 19 columns and 377 rows x 19 columns for oil and gas production data respectively. These data are reliable since they came from an official government website. 

<p align="center">
  <img width="300" height="100" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/Methodology.jpg">
</p>

The workflow above illustrates an overview of how I performed this project using North Dakota oil and gas production data. To begin with, the target webpage was used to find any data related to county oil and gas production in North Dakota. Moreover, web scraping has been performed to retrieve target files which available in pdf format. Furthermore, the downloaded pdf files will be automatically converted into csv files and stored in the database for further analysis. Finally, the datasets were ready and used to analyze and visualize the total oil and gas production in North Dakota.

## III. Results
In the first plot below, a time series plot was conducted to identify the trend of oil production by counties in North Dakota from 1951-2021. It seems that the rising of oil production began in 2008 which was started by Mountrail county and followed by other counties such as Williams, Dunn, and McKenzie in the next couple of years. This might have happened due to unconventional fracture booming. For the last 10 years in the second plot, it was quite fluctuating from 2015-2019 with the peak of oil production was in 2019.

<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-01.png">
</p>
<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-02.png">
</p>

For gas production analyses, a time series plot was built from 1990-2021 to identify trend in North Dakota counties. The gas production has begun to increase in 2010 and again probably due to the same reason, the unconventional fracture booming. For the past 10 years, it seems that gas production has steadily increased compared to oil production until reached the peak of gas production in 2019.

<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-03.png">
</p>
<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-04.png">
</p>

The total of oil and gas production was dominated by several counties that include Dunn, McKenzie, Mountrail, and Williams among 19 counties. Therefore, I am interested to see the dominated county's production in the past 10 years. In oil production, Mountrail was the leader from 2011-2012 until McKenzie overtook the production since 2013 until now while the gas production has been led by McKenzie county since 2011.

<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-05.png">
</p>
<p align="center">
  <img width="500" height="200" src="https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-06.png">
</p>

Based on various time series plots above, there was a significant decrease in both oil and gas production that started in 2020-2021. Although in 2021 production data only consisting of Q1 data, this declining event might have been caused by the global pandemic COVID-19 that started in early 2020 and driven oil prices to drop below zero for the first time in trading history. These plots below demonstrate the present total oil and gas production in North Dakota.

<p float="middle">
  <img src = "https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-07.png" width = "48%" height = "48%"/>
  <img src = "https://github.com/a-pradono/north-dakota-production/blob/main/Images/plot-08.png" width = "48%" height = "48%"/>
</p>

## IV. Conclusions
The main objective of this project was to save time on data collection by making it automatically from web scraping and transforming pdf into csv formats for further analysis of oil and gas production in North Dakota. The conclusions made from this project are:
  * Time was efficiently reduced by 88 % with the assumption from manual typing of multiple pages pdf could take 8 hours working time.
  * Total oil and gas production in North Dakota has begun to rise in 2008 due to unconventional fracture booming.
  * Top oil and gas producing counties are dominated by McKenzie, Mountrail, Dunn, and Williams among other 16 counties.
  * The significant declined in total oil and gas production since 2020 might have been caused by the global pandemic that led to negative oil prices.
