# Abalones_Statistical_Analysis

## Data Analysis Overview:
Two data analysis projects using abalone data are required in this course. The first project entails exploratory data analysis. The second project involves statistical inference using analysis of variance and linear regression. Binary decision rules will be evaluated and a Receiver Operating Characteristic (ROC) curve developed.

## Overall Background:
We are bombarded daily with statements or claims arising from surveys and studies that use data to generate statistics. In a world where data are becoming more abundant every day, as an educated consumer, it is essential to think critically about the information we receive and the decisions that will be made based on that information. Part of this involves considering the source of the data, how it was collected, how it was analyzed and whatever limitations there may be to the conclusions reached and claims being made.

## Project Background:
Abalones are an economic and recreational resource that is threatened by a variety of factors which include: pollution, disease, loss of habitat, predation, commercial harvesting, sport fishing and illegal harvesting. Environmental variation and the availability of nutrients affect the growth and maturation rate of abalones. Over the last 20+ years it is estimated the commercial catch of abalone worldwide has declined in the neighborhood of 40%. Abalones are easily over harvested because of slow growth rates and variable reproductive success. Being able to quickly determine the age composition of a regional abalone population would be an important capability. The information so derived could be used to manage harvesting requirements.

#### Supplemental information may be obtained from the following sources:
http://www.fishtech.com/facts.html http://www.marinebio.net/marinescience/06future/abintro.html


## Background information concerning the assignment data:
The assignment data are derived from an observational study of abalones. The intent of the investigators was to predict the age of abalone from physical measurements thus avoiding the necessity of counting growth rings for aging. Ideally, a growth ring is produced each year of age. Currently, age is determined by drilling the shell and counting the number of shell rings using a microscope. This is a difficult and time consuming process. Ring clarity can be an issue. At the completion of the breeding season sexing abalone can be difficult. Similar difficulties are experienced when trying to determine the sex of immature abalone.
The study was not successful. The investigators concluded additional information would be required such as weather patterns and location which affect food availability.
Assignment 1 is an exploratory data analysis to determine plausible reasons why the original study was unsuccessful in predicting abalone age based on physical characteristics.
Assignment 2 will involve development of a regression model; and, also address development of binary decision rules and a Receiver Operating Characteristic (ROC) curve.

## Data set: abalones.csv

## Data Description: 
This data file is derived from study of abalones in Tasmania. There are 1036 observations and eight variables. The CLASS variable has been added for this assignment.

1. SEX=M(male), F (female), I (infant)
2. LENGTH= Longest shell length in cm
3. DIAM = Diameter perpendicular to length in cm
4. HEIGHT = Height perpendicular to length and diameter in cm
5. WHOLE = Whole weight of abalone in grams
6. SHUCK = Shucked weight of meat in grams
7. RINGS = Age (+1.5 gives the age in years)
8. CLASS = Age classification based on RINGS (A1= youngest,., A6=oldest)


