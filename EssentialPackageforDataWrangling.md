# Essential Packages for data wrangling

*Install package Panda :* 

                pip install panda

*Import panda package :* 

                Import pandas as pd
                 
## To read a CSV file : 

*Procedure explanation :* 
                Panda is installed because panda has DataFrame property, CSV file will be imported to that Data Frame.                 
                Below is a sample code: This two line of code will load a CSV file and print the first 10 rows in your terminal window. For IDE Visual Studio Code is used with the Jupyter       extention. 
                
                df = pd.read_csv(file_path, sep = ",\s+", header = 0, engine = 'python') 
                print(df.head())

*To know how the data looks like :*
                to know the names & number of columns the dataframe have this two lines will do the magic : 
                
                for col in df.columns: 
                    print(col)
                
  Also to know the column data types :  
  
                print(df.dtypes)
