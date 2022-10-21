# DATA MODELING WITH POWER BI

*Normalizing Data and Creating Meaningful Insights*

---

# DATA MODELING:
Data modeling is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures. The goal is to illustrate the types of data used and stored within the system, the relationships among these data types, the ways the data can be grouped and organized and its formats and attributes.Data modelling is a technique used in NORMALIZING data ,that is breaking them down into a fact table and dimension table.

Data models are built around business needs. Rules and requirements are defined upfront through feedback from business stakeholders so they can be incorporated into the design of a new system or adapted in the iteration of an existing one. In this project, Data is normalized on the basis of permannent data and the continuous data for better understanding of the relationships between the datasets.

---
#                                                           CaseStudy: *SUPERSTORE DATA*

# DATA SOURCING:
The data used in this project is sourced from the given github repository: https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/tree/main/Data%20Modelling%20Dataset

# NORMALIZING DATA

The given data is in the form of table which include all the permanent and the continuous data. Firstly, I seperate the data into seperate sheets of **SALES**, **PRODUCT**, **COUSTOMER**, **SALES REP**, and **LOCATIONS**. 
![denormalized SalesData](https://user-images.githubusercontent.com/107538510/175783961-4fb009fe-1c89-4861-9a76-b6184f1f474d.PNG)
After seperating the columns into different sheets
![normalized data](https://user-images.githubusercontent.com/107538510/175783987-080e0d3c-94b7-4bf9-a2c1-f05d7a04e9e9.PNG)

# DATA MODELING IN POWER BI:

After normalizing the data, I just upload MS EXCEL data file in the Power BI where the power query is opened. I then clean and modify the data by making some changes like the first row assign ass header row and deleting unnecessary blank rows in the power query. Then load the data in Power BI. After checking the above tabs, I opened the model tab view and connect the fact table (permanent data table) keys to the dimension (continuous data table)keys.
![model tab](https://user-images.githubusercontent.com/107538510/175784265-aaf85467-050f-438b-b2ab-05306f2c75fb.PNG)

# REPORT IN POWER BI:

After building the relationship between different tables, it is easier to visualise the data for quick and bettter understanding of the Sales to region and to find the maximum Number of Sales done by which Salesperson. ALl the insights shows the answers to every question about sales, customer, profit, and the regions where maximum sales are done.
![Sales data modeling dashboardby Power BI](https://user-images.githubusercontent.com/107538510/175784395-7a8a9c8b-9f4b-4605-b3cd-3b4cf6fa2c7a.PNG)
