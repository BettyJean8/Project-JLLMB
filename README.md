# Group Project One 
## Readme to be added to 
Description:
The Project Scope will include the data visualization and analysis of housing data for select cities in MN from the last 5 years (2018 – 2023). The cities in question will be Duluth, Rochester, and Minneapolis. The assessment will consider exclusively Single-Family Homes for rentals and houses. Comparisons will also be made to the USA.
The pricing of these homes to obtain the median range  is from the 35th – 65th Percentile (Middle third), (per the Zillow data extract), to avoid having outliers skew the data. The data obtained are ZHVI and ZORI.

Dependancies to install:
1. import matplotlib.pyplot as plt
2. import pandas as pd

How to run:
Download Dependancies
Open and run jupyter notebook "Housing.ipynb" 

Sources:
1. https://www.zillow.com/research/zhvi-user-guide/
2. https://www.zillow.com/research/data/
3. Zillow ZVHI (Zillow Home Value Index)
4. Zillow ZORI (Zillow Observed Rent Index)
5. https://pandas.pydata.org/docs/
6. https://matplotlib.org/stable/api/index.html
7. ChatGPT for debugging
8. Xpert Learning Assist


Collaborators

1. Jenna A.
2. Luis F.
3. Luke M.
4. Matt M.
5. Britta N.

# Link to Slide Show https://docs.google.com/presentation/d/1WGvCUBBlI1A4toasszKNOhl3mSzRQ-iT8hwex-zY5bo/edit?usp=sharing
## Notes
2024 Data is incomplete and was included to add some additional research in various charts. Trends will likely be lower due to partial data. 
There was 1 NAN value in the dataset. The data between the 2 months trended downwards so merged_df.bfill()  # Backward fill was used to fill in the data. 
