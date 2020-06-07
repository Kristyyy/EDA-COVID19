# covid-19-data

## Purpose of my analysis

Recently the world is facing with the outbreak of COVID19. From the analysis, I hope I can find out which state in U.S.A is the most servere and the overall trend in the period. I want to compare the most severe state with California, which I am now living at to find out the difference. I also want to find out will the increase of COVID cases increase the amount of deaths.

## Outline of the analysis
First, I will use geopandas to make a map to show which state has the higest cases and deaths.

Second, I will analysis the data of the most severe state

Third, analysis the state of California where I am now living at

Forth, compare the most severe state with California and find the difference between them. I will show the mean, standard deviation, and the time series.

In the end, I will show the scatter plot with linear regression line of best fit to find out if there is any positive correlation between cases and deaths.

## Introduction to COVID dataset

The dataset I choose reveal the state data of COVID cumulative cases and deaths in America. The time period is from the outbreak to April 8th.

Features description:

date: From the outbreak of the COVID cases and deaths to April 8th

state: each state in America

fips: encode for each state, I will use it to merge the dataframe of geo dataset

cases: cumulative cases in America

deaths: cumulative deaths in America
