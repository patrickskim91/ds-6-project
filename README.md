# Module 6 Projects
* Student Name: PATRICK KIM
* Program: Data Science 
* Cohort: 06/24/19
* Due Date: 10/04/19
* Instructor: HOWARD SMITH


# Project Overview


## Context
Since it's inception in 2008, Airbnb has disrupted the traditional hospitality industry as more and more travelers are opting to choose Airbnb as their primary accommodation provider. Initially starting off with two bookings, Airbnb has now grown to host over six million listings worldwide across over 100 thousand cities.

In the United States of America, Airbnb has reached markets across the nation. In California, no city is more popular than Los Angeles. With over 44,500 listings as of July 2019, Los Angeles is the second largest host city behind New York City. With a size of 503 $mi^{2}$, this means there are roughly 88 listings being rented our per $mi^{2}$ in Los Angeles on Airbnb!

## Content
The dataset consists of multiple files that house various points of data. We will be using the files listed in bold. Below are the file descriptions:
* **listings.csv** - detailed listings data for each rental (name, bedrooms, bath, sq ft, location, etc.)
* reviews.csv - detailed review data for each rental (listing ID, review date, comments, etc.)
* calendar.csv - detailed calendar data for each rental (booking status, date of booking, etc.)
* neighbourhoods.csv - summary list of every neighborhood in Los Angeles
* neighbourhoods.geojson - GeoJSON file of neighbourhoods of the city

## Acknowledgment
The data is available at: http://insideairbnb.com

Inside Airbnb is an independent, non-commercial set of tools and data that allows you to explore how Airbnb is really being used in cities around the world. 

## Goal
The goal of this notebook is to use linear regression models to analyze data trends to **help Airbnb host better understand the hospitality market and to use this gained knowledge to make informed decisions regarding their listing(s).** The following questions will drive this project:
* **Can we predict daily prices for a listing that fits into its specific market environment and competitors in Los Angeles?**


## Approach
The **OSEMiN Process** is an acronym that stands for **Obtain, Scrub, Explore, Model, and iNterpret**. It is used as a blueprint for working on data problems using machine learning tools. Preprocessing involves scrubbing (also called cleaning) and exploring the data. Building the model, evaluating, and optimizing it make up the process of machine learning.