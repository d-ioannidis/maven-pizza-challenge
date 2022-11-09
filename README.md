Python code to prepare data for the Maven Pizza Challenge. The data is correlated to a fictitious 
Greek-inspired pizza place in New Jersey, called Plato's Pizza. Playing the role of an BI Consultant,
the task is to help a restaurant overview and improve its operations performance through the given data.

The end goal is to create a single page dashboard visualization, ultimately being the challenge's 
final objective. The final product is a separate interactive Power BI dashboard.

The dataset in total includes 4 tables

* The **Orders** table contains the date & time that all table orders were placed. 
* The **Order Details** table contains the different pizzas served with each order in 
  the Orders table, and their quantities.
* The **Pizzas** table contains the size and price for each distinct pizza in the Order Details 
  table, as well as its broader pizza type.
* The **Pizza Types** table contains details on the pizza types in the Pizzas table, including their 
  name as it appears on the menu, 
  the category it falls under, and its list of ingredients.
  
The datasets comes with separate tables as mentioned above, with each table being its own CSV file. 
The initial steps are to read said tables and create Pandas DataFrames with similar names. Afterwards,
data cleaning, merging and aggregation processes took place to organize all tables into one large single
table where it's later converted into a CSV file which is then used by Power BI for the visualization 
part of the challenge.

Technologies used:

* Base Python 
* NumPy
* Pandas
* Power BI

The Power BI dashboard can be viewed through this link:
https://community.powerbi.com/t5/Data-Stories-Gallery/Maven-Pizza-Challenge/m-p/2854624

***Note:** Initial experimentations included the usage of Plotly and/or Matplotlib before resorting
to the use of Power BI for the final visualization process.
