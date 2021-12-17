# Class-201- 
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline


df = pd.read_csv('https://raw.githubusercontent.com/CunyLaguardiaDataAnalytics/datasets/master/2014-15_To_2016-17_School-_Level_NYC_Regents_Report_For_All_Variables.csv')


df.head()

df.describe()


df['School DBN']


df[['School DBN','School Name' ]]

df['School DBN'].describe()

df['Total Tested'].describe()

df['Percent Scoring 80 or Above'].describe()

df['Percent Scoring Below 65'].describe()

df['School Name'].describe()

df.hist()

df.plot()

df.plot(kind='hist')

df.plot(kind='scatter', x='Year', y='Total Tested')

df.plot(x='School DBN',y='Total Tested')

## Conclusion: The total school tested are 212331 the District Borough Number (DBN)report 1018 tested.The total tested report a good 
##amount of respont to be  tested in al district borough it si confirm the graph Year & Total Tested. Also the graph School DBN & Total Tested
##report the small amount of with schools with top level; just the New Vision Charter High School for Advanced Math & Science report high levels.
##it conclude the total amount of avg. is in general good level of schools district borough having in consideration the diversity of population of city
##the school district. 
