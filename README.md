
# MyBank
## Automating Day Job using Python
### Background
Welcome to the world of Python programming. I will be using some of the concepts of Python that I learned to complete the PyBank casestudy related to the company ABC Inc. The data I will be using is from Jan 2010 to Feb 2017. 

![abc inc](https://user-images.githubusercontent.com/83671629/119518260-5e286c80-bd46-11eb-9305-f3a1fd708815.png)


## To Begin with
  1) I created a new GitHub repo and cloned it to my computer.
  
  2) In my local git repository, I created a directory named **PyBank**.
  3) Using JupyterLab I created a .ipynb file to write the pyton code.
  4) Named the file as **FinalAssig_2a**
  5) I pushed all the changes to GitHub

## PyBank
![Rev](https://user-images.githubusercontent.com/83671629/119515011-7d71ca80-bd43-11eb-9383-d5c57a2a9e99.jpg)

In this casestudy, I will be creating a Python script for analyzing the financial records of ABC Inc. The required Financial dataset is in this file: [revenue_data.csv](revenue_data.csv). This dataset is composed of two columns, Date and Profit/Losses. 

I will be creating a Python script that analyzes the records to calculate each of the following :

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the changes in Profit/Losses over the entire period.

* The greatest increase in profits (date and amount) over the entire period.

* The greatest decrease in losses (date and amount) over the entire period.

The resulting analysis will look similar to the following:

  
  Financial Analysis
  ----------------------------
  Total Months: 86
  
  Total: $38382578
  
  Average  Change: $-2315.12
  
  Greatest Increase in Profits: Feb-2012 ($1926159)
  
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  
  ## Calculations
  
  Total number of months were calculated by using the "len()" built in function of Python. This gives the numbers of recods in the file.
  
  Total sum total of all the profit and losses during the period was calculated by looping over each record using "While" loop and adding the profit/losses field to a variable.
  
  Average changes is by finding the change in profit/losses between the last month and the first month. This is divided by the number of changes in the profit/losses (i.e total recodes less one).
  
  Here are some link to help understand the calcylation of Average Change.
 
  https://byjus.com/average-rate-of-change-formula/
  https://www.omnicalculator.com/math/average-rate-of-change
  
  https://mathbitsnotebook.com/Algebra2/FunctionGraphs/FGAverageRateChange.html
  
  
  The greatest Increase in the profit is calculated using the built in Python function max().
  The greatest decrease in the profit is calculated using the built in Python function min().
  I created an empty list to hold all the month by month changes over the entire period.
  Using a While loop I appended each diffrence in profit to this empty list.
  The 
  
  

## 
