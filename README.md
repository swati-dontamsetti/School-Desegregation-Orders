# School-Desegregation-Orders

Analyzing this data set: https://www.propublica.org/datastore/dataset/school-desegregation-orders-data

"Across the United States, some school districts are bound by orders to increase the racial integration of black and Latino students and improve their educational opportunities. This dataset collects information about all of those school desegregation orders, from 1957 through the end of 2014. 

The data files include information about school desegregation orders mandated by federal courts and open school desegregation orders that resulted from voluntary agreements between school districts and the U.S. Department of Education’s Office of Civil Rights."

Looking for:
1. Location of the orders
<br>a. According to National Geographic, the United States is typically divided into five geographic regions: the Northeast, Southwest, West, Southeast and Midwest.
2. Number of orders by years
<br>a. Has there been more or less orders over time?
3. Where are the most, and most recent orders taking place?
4. What assumptions about segregation and location are confirmed and overturned?

## Hypothesis
We assume that the South is more discriminatory than the North, because of it's history of slavery and Jim Crow. But, while the South was forced to desegragate through mandated busing, and other federal orders, the North was allowed to quitely segregate its counties through redlining. I predict that more of the recent desegregating order will take place in states we view as liberal.


## Progress Update
I started the cleaning process. I have currently used Jupyter Notebook to go through both CSVs to change NAs into "Unknown year" to keep with other columns, delete unneccessary columns, format the date, and add a necessary column.

I used a long and tedious but effective for loop combined with if else statements to added the Regions based on the State.

Started to analyze the data. Just wanted to see what the count per region was to see if anything stuck out. It showed me that voluntary and involuntary orders were ranked differently. So I thought maybe I should add a "history of slavery" column as well. I decided to qualify the history of slavery by filtering the states that were free before the Civil War or became free during it. And the slave states were those that were part of the Confederacy and were willing to break from the Union in order to keep the institution of slavery. There were a few states that were border states (those that had slavery but were part of the Union). And a few states were territories and weren't US states yet. (1/29/21)
