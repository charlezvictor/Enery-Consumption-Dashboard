# Energy-Consumption-Dashboard
 
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/lightbulbs1-1350x720.jpg)

### User Friendly Intercative Power BI dashboard showing Energy Consumption of Cities across the United States
---

## INTRODUCTION
---
A power BI project to craete a viz showing energy consumption and cost accross states in the United States carried out to derive insights from previous year sales in order to make data driven decisions.

## DATA SOURCING
---
**_Disclaimer_**: _This dataset and report is just a dummy dataset to showcase several functionalities of Power BI._ 
Dataset can be found [here](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Energy%20Consumptions%20Dataset.xlsx)

Dataset contains three sheets:
1. Energy Consumptions - Energy consumption of buildings across 3 years
2. Rates - Showing price per unit on the various type of enegry across 3 years
3. Buliding Masters - Showing locations of buildings across USA 

## PROBLEM STATEMENT
---
1.	Total Amount spent on energy consumption?
2.	Total units consumed?
3.	Cost of energy over the years?
4.	Unit consumed per building?



## SKILLS / CONCEPT DEMONSTRATED
---
The following Power BI concepts were put in place
-	DAX
- Data Transformation
-	Quick measures
-	Data Modelling
-	Tooltips
- Page Navigation
- Button
- Bookmarks and Selection panel

## DATA TRANSFORMATION
---
Data was generally clean, but in order to enable data modelling, I had to create a key in two tables (_Energy Consumption and Rates_) to help Power BI identify on which column to join both table.
This was done by creating a new column, extracting the year from the energy consuption dataset and creating a merge column of both the years and teh energy type columns.
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/creating%20key.png)


## MODELLING
---
Power BI as it would usually do, automatically derived a relationship between tables which were accurate, craeting a star schema data model structure. 
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Data%20Modelling.png)


## VISUALIZATION
---

![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Nav%20Page.png)
---

#### Features
 KPI showing
-	Total Cost of Energy for all energy types 
-	Total units consumed for all energy types
Total cost by city
Total cost by date and consumption type
Unit consumed by type
Unit consumed by building


### Download PowerBI report [here](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Energy%20Dashboard.pbix) and interact with it 

You can downlaod a Pdf version of the report [here](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Energy%20Dashboard.pdf)

## KEY PROCESS INVOLVED
---
Processes involved on how certain mesaures were created that aided in developing this dashboard includes:

##### 1.  Creating Quick Measures
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Measure%20Calc.png)

##### 2.  Creating new pages showing KPI for the different forms of energy
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Overview.png)
### Overview 
---
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Water.png)
### Water 
---
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Gas.png)
### Gas
---
---![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Electricity.png)
### Electricity
---

#### 3. Creating Page Navigation and Buttons
![](https://github.com/charlezvictor/Enery-Consumption-Dashboard/blob/main/Bookmark%20%26%20Selection.png)


 


## Thank You
![](https://github.com/charlezvictor/Sales_Analysis_Viz/blob/main/Thank%20you.jpg)





I'm available to answer any questions and receive any recommendations you have concerning this project.
Let's connect on [Linkedin](https://www.linkedin.com/in/victor-onyeaghala-08a909167/) and on [Twitter](https://www.twitter.com/_char_lez)
