# data_collection
Module 11

Description:
Part 1 - Extracted the titles and previews text of the news articles that i scrapped from website: https://static.bc-edx.com/data/web/mars_news/index.html
    Saved the outcomes into JSON format.
Part 2- Extracted all the rows of data table from website: https://static.bc-edx.com/data/web/mars_facts/temperature.html
    The data was converted into dataframe and then used for different visualizations
Installation:
Relevant libraries were imported for this project such as :
    from splinter import Browser
    from bs4 import BeautifulSoup as soup
    import json
    import matplotlib.pyplot as plt
    import pandas as pd


Usage:
Part 1: Used to read only the news and its preview.

Part 2: Used to analyze and visualize the data captured on Mars.
        It help us understanding the minimum temperature across the months on Mars.
        Month vs atmospheric temperature of Mars.
        Terrestrial days vs minimum temperature on Mars.


Configuration:
Its important to have pandas intalled on PC and VS code /Jupyter notebook. 
Must be run in dev environment
Chrome is compulsory to download.


Acknowledgments:
I acknowlege the support of my teachers and the resources they have provided. 


