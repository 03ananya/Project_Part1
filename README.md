# Project_Part1

Data-512-project-part 1
================================
This repository contains the part 1 of the Common analysis for DATA 512 course project

Goal: Course Project
==============================
During the last three years we all have been experiencing a global pandemic. This has been tragic and disruptive to many countries and has taken a deep personal toll on many individuals and their families. 
One aspect that has been hard to miss in the last three years is the datafication of the pandemic. That is, many aspects of the individual toll of the pandemic have been collected, aggregated and re-represented as data. This datafication gives us the privilege to examine the pandemic from potentially many different perspectives to understand how it has changed lives and how it has changed society. To be honest, we are actually at the very beginning of understanding and comprehending these impacts.
During this Course Project we took a look at some of the social aspects of the pandemic by conducting a human centered data science analysis of some available COVID-19 data. 

County Assigned: Harris County, Texas

Data Information
----------------------

Datasets
-   RAW_us_confirmed_cases.csv - Consists of daily confirmed COVID cases for all counties from from the Kaggle repository of John Hopkins University COVID-19 data. 
    
-   mask-mandate.csv - Mask mandate information from The New York Times mask compliance survey data.

-   mask-use-by-county.csv - Survey that contains the percent values of mask compliance based on level of compliance collected by CDC

Issues and Special Considerations
---------------------------------

1.  The 3 datasets given have different structures and in order to use them together we had to do some preprocessing as can be seen in first part of the code.
2.  There are assumptions made here to simplify the analysis. For example, we do not consider the effect of vaccinations on the spread of covid.

Repository Structure
--------------------

├── Data512-part1.ipynb
├── README.md
├── LICENSE
├── data
│   ├── RAW_us_confirmed_cases.csv
│   ├── mask-mandate.csv
│   └── mask-use-by-county.csv
├── Reflection_Statement.pdf
├── Visualization_Explanation.pdf
├── plots
│   ├── Number_of_cases_cumulative.png
│   ├── Number_of_cases_daily.png
│   ├── Infection_rate.png
│   ├── Second_order_differencing_of_Infection_Rate'.jpeg
│   ├── Second order difference of the numner of COVID cases daily.jpeg



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Plots

 ![1](https://github.com/03ananya/Project_Part1/blob/main/Plots/Cumulative%20number%20of%20COVID%20cases-%20Harris%20County.jpeg

 ![2](https://github.com/03ananya/Project_Part1/blob/main/Plots/Infection%20rate%20of%20Harris%20county.jpeg)

![3](https://github.com/03ananya/Project_Part1/blob/main/Plots/Growth%20of%20Infection%20Rate.jpeg)

![4](https://github.com/03ananya/Project_Part1/blob/main/Plots/Second%20order%20differencing%20%20of%20Infection%20Rate.jpeg)

![5](https://github.com/03ananya/Project_Part1/blob/main/Plots/Second%20order%20difference%20of%20the%20numner%20of%20COVID%20cases%20daily.jpeg)



