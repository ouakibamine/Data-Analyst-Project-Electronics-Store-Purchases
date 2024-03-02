# Pandas-Data-Science-Tasks
Set of real world data science tasks completed using the Python Pandas,matplotlib,seaborn,prophet,numpy,glob,itertools librarys.

## Setup

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Installing Pandas library: pip install pandas
Installing prophet library: pip install prophet
Installing matplotlib library: pip install matplotlib
Installing glob library: pip install glob
Installing itertools library: pip install itertools
## Background Information:

I use Python Pandas & Python Matplotlib to analyze and answer business questions about 5 years worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)


To answer these questions bellow we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 11 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
![Image](images/Q1.png)
- What's the year when we had a heighest number of Sales ?
![Image](images/Q2.png)
- What city sold the most product?
![Image](images/Q3.png)
- What products are most often sold together?
![Image](images/Q4.png)
- What product sold the most? Why do you think it sold the most?
![Image](images/Q5.png)
- Overall trend in sales over the given period 
![Image](images/Q6.png)
- Top selling products by quantity ordered and revenue generated
![Image](images/Q7.png)
- Correlation between price of a product and quantity ordered
![Image](images/Q8.png)
- Sales performance across different cities
![Image](images/Q9.png)
- Forcasting Sales for casablanca city in the next 4 months 
![Image](images/Q10.png)