# Wrangle and Analyze Data from WeRateDogs

## Introduction

Real-world data rarely comes clean. This project is made using Python and its libraries: I gathered data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. 

The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs, with over 4 million followers. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators are almost always greater than 10 because "they're good dogs Brent." 

This project was already reviewed and met all the specifications. 


## Project Overview

This Project was divided into 5 parts:

### Part I - Gathering Data
First I gathered all three pieces of data:
1. The WeRateDogs Twitter archive: a file on hand.
2. The tweet image predictions: downloaded programmatically
3. Data from the Twitter API.

### Part II - Assessing Data
After gathering all three pieces of data, I assessed them visually and programmatically for quality and tidiness issues. Note that there are more issues pending.

### Part III - Cleaning Data
I cleaned all of the issues I documented while assessing, using the define-code-test framework and documenting it.

### Part IV - Analyzing and Visualizing Data
Once stored data, I analyzed and made visualizations of wrangled data. I tried to ask 5 questions and then answer them.

### Part V - Reporting
I created 2 reports:
1. A wrangle report that describes my wrangling efforts, framed as an internal document.
2. An act report that communicates all the insights and displays the visualizations produced, framed as an external document (like a blog post).


#### What you may know about this Jupyter Notebook
The following libraries need to be installed:
- Numpy
- Pandas
- Matplotlib
- Requests
- Tweepy
- Json
- Timeit

This is a project from Udacity website for the *Data Analyst* Nanodegree. Part of the guide text was provided by Udacity.