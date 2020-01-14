# real_estate_analysis
Analyzing real estate with data from popular real estate sites


import pandas as pd
import numpy as np 
from bs4 import BeautifulSoup
from urllib.request import urlopen


# look into Trulia and Redfin -focus in Brooklyn
trulia_url = 'https://www.trulia.com/NY/Brooklyn/'
trulia_response = requests.get(trulia_url)

redfin_url = 
redfin_response = 

soup = BeautifulSoup(trulia_url, 'html.parser')
soup.prettify()
soup.find_all( 'div' ,attr
