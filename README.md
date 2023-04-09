Language : Python 
CodeSpace: Notebook Jupyter

# csv-update-

Import the liberies 
import csv
import pandas as pd
from datetime import date

try:
    
    #Loading and reading the file
    rdb = pd.read_csv('xxx.csv')   

except Exception:
    
    print ("System error occurred, try again")

#Output the dataframe
rdb
