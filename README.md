# pandas-challenge

Analysis of school and standardized testing using pandas DataFrames in Jupyter Notebook

## Instructions / Premise

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Modules

pandas
pathlib

## Summary

This script reads in two csv files of student and school data, merges them and then builds out analytical summaries using mostly groupby aggregate functions. The code is built so it could be repeated for varying school boards so long as the input data was formatted the same way in the original csv files. Where possible, I used .map formatting for readability by rounding decimals. You will see a couple of places it is skipped -- only because that particular dataframe is needed for future calculations. An exception to this is the original summary dataframe, for which I saved a separate unformatted version for later calculations and also displayed a formatted version for the reader. Also included is a summary analysis of what the data shows for the "mayor and school board" that has hired us to do this analysis. 

## Citations

The vast majority of the code came from in-class learnings, as well as the guide code left in the original download file. Google helped with one small exception:

- Replacing the index in the first summary dataframe. I wanted to get rid of the zero that appeared. Found this solution: (https://stackoverflow.com/questions/40427943/how-do-i-change-a-single-index-value-in-pandas-dataframe)