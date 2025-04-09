# Project-2
### Name: Asha Cumberbatch 
### Date: April 8th
### Assignment: Project 2 part 2 - Employment table
### Purpose: The aim of this notebook is to pull the data from the table on the List of U.S. states by employment rate Wikipedia page (https://en.wikipedia.org/wiki/List_of_U.S._states_by_employment_rate). The page will be web scraped and the data cleaned. 
### The columns of particular interest are State, and Employment rate in % (total population), and will be saved to a csv file. That csv file will be merged with other csv files, created from similar pages, then saved as a new data frame. The resulting data frame will be used to gain insight on how these metrics differ by state.
##### The first step is be to import the necessary packages. BeautifulSoup, imported as bs, and pandas, imported as pd will be needed.
import requests
from bs4 import BeautifulSoup as bs
import pandas as pd
