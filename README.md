---
title: "README"
output: html_document
---

The objective of this project is to determining abundance over time with 
focus on the East Coast of the United Stated for white shrimp (Litopenaeus 
setiferus). This will be done to determine if there has been changes in 
abundance over time and explore if there is an association with environmental 
variables and abundance.

The data is taken from SEAMAP's Coastal Trawl Survey, NEAMAP's trawl survey, 
and ChesMMap's trawl survey. The data set provided in this portion of the 
project includes data from 2008 to current (i.e.2022-2023). While more data is 
available, only a subset has been provided. 

The key categories from the data that will be used are listed and described 
below:
Year- year the particular trawl occured 
Count/Towtotal- the total number of specimens from a particular study that were 
caught during that trawl 
ELAT/lat and ELON/lon- longitude and latitude of trawl start point
BTEMP/WT- bottom temperature/water temp of water 
BSAL/SA- bottom salinity/salinity of the water 

Instructions for each step are included in the script of the file however the 
general project instructions are as follows:
1. Establish data sets and what data columns will be used from each
2. Upload data sets into R. Naming is important. Keep names of data sets short
as they will be added onto for each step (ex. shrimpSM will become 
shrimpSMtotals).
3. Recommended but not necessary: create a summary of each data set 
4. Create a map of all the trawl locations using latitude and longitude 
data.
5. Calculate the total number caught each year. Plot for each survey.
6. Create a map of the total number of caught based on abundance. Exclude 
trawls with 0 catches. This acts more as a presence/absence plot but is good 
visualization for where specimens are caught and allows you to display them by 
how many were caught there as well as indicate any changes in abundance by year.
7. Calculate and plot the total positive catches (catch > 0) for each year.
8. Calculate and plot average water temperature and abundance each year.
9. Begin fitting models to a linear model using water temperature and salinity 
as the explanatory variables to determine their effect on abundance. 
Each variable should have its own model.
10. Plot the residuals and test for normality.
11. Fit the variables to a GAM. 


Current predictions for results do not expect to find salinity as a good 
explanatory variable for shrimp abundance. Temperature is expected to have more 
of an effect, however because shrimp are highly dependent on environmental 
conditions year to year, no patterns are expected in their abundance. 


Data was provided through SCDNR and VIMS. 









