# Bike Buyers Dashboard - Excel Project

This Excel project is inspired by the tutorial "Full Project in Excel | Excel Tutorials for Beginners" by 'Alex The Analyst'.

Using the provided bike buyers dataset, I created a dashboard to gain insights into customer behavior. Below are the steps followed in this Excel project:

### Data Cleaning

1. Remove all duplicates

- Used the Data Tool to eliminate duplicates.
- Outcome: 26 duplicate rows were removed.
- Remaining rows: 1001 unique entries.

2. Find and Replace
   In the Marital Single Column:

- Replace 'M' with 'Married'
- Replace 'S' with 'Single'

In the Gender Column:

- Replace 'F' with 'Female'
- Replace 'M' with 'Male'

3. Fix the format of Income to currency

4. Add a column to group the age interval
   =if(L2>54,"Old", if(L2>=31,"Middle Age”,if(L2<31,"Adolescent","Invalid")))

### Pivot Tables

* Three pivot tables were created to explore the data: Average Income Per Purchase, Customer Commute, and Customer Age Brackets. Key observations include:
     * Income vs. Bike Purchase: Customers with higher incomes are more likely to buy a bike. Additionally, the average income of male customers is higher than that of female customers.
     * Commute Distance: Surprisingly, customers with shorter commutes are more inclined to purchase a bike, possibly because those with longer commutes prefer other transportation modes for 
       convenience.
     *Age Groups: The middle-aged group (31-54 years) has the highest number of bike purchases.

### Dashboard

The final dashboard neatly displays all the graphs with interactive slicers for filtering by Marital Status, Region, and Education level.
