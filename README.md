# Project Pizza Sales Analysis Using SQL and Power BI
Developed an insightful Pizza Sales Analysis dashboard using Power BI and SQL to provide insights to the Sales Team.

## Objective:
The objective of this project is to comprehensively analyse the raw data and provide actionable insights through a dashboard for improving total sales of a pizza shop. These  insights will prove helpful for the sales team for their further analysis.
Throughout this project, I've had the chance to:<br />
  * Dive deep into Pizza Sales data to uncover valuable insights. <br />
  * Develop interactive dashboards to visualise key Pizza Sales metrics.<br />
  * Provide data-driven recommendations for strategic decision-making.

## Steps Followed:
### 1. Data Gathering:
Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
### 2. Data cleaning:
* Cleaning is done by removing empty columns, removing duplicates, errors etc.<br />
* Replacing values in column with proper values and naming.
* Detecting data type of every column, using the auto detect data type function in Power query editor and performing manual cross check.
### 3. Data processing:
* In the Power Query editor, a new table called "Measure Table" was created  by using the DAX expression.Further new measures were created under this table such as Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, Average Pizza Per Orders. <br />
* In DAX Query view, new Table called as “Calendar dimension” is added along with various new columns like Month, Month Number, Quarter, Year etc for performing Time Intelligence Functions
### 4. Data Modelling:
 In Model View, One to Many relationships were established between dimension tables and fact tables. For this Star Schema is used.
### 5. Data analysis:
* Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, area charts, donut & pie charts,line charts and other relevant visualisations.<br />
* These tools are utilised to gain insights and present data in a comprehensive and easily understandable manner.

## Key Questions of The Dashboard:
* What is the Total Revenue and Total Orders?<br />
* What is the Total Quantity Sold?<br />
* What are the Top 5 and Bottom 5 pizzas by Revenue?<br />
* What are the Top 5 and Bottom 5 pizzas by Quantity?<br />
* What are the Top 5 and Bottom 5 pizzas by Total Orders?<br />
* What are Best and Worst seller pizzas in terms of Revenue, Quantity and Total Orders?<br />
* How are the Daily and Monthly trends of pizzas with respect to Total Orders?<br />
* What is the percentage distribution of pizzas by Category and Pizza Size?<br />
## Learned About: 
* Calculated Fields <br />
* Donut chart and Area Chart<br />
* Bar Chart and Cluster chart 📊<br />
* KPI(Key Performance Indicators) and Slicer.<br />
* Filters: Used to filter data according to different City and Brands.<br />
* Time Intelligence Functions <br />

## Key Insights Summary:
Analysed historical pizza sales data using SQL Server Management Studio and Power BI to identify: - <br />


* Daily Trend (identified 34% more sales on Friday with respect to lowest on Sunday) <br />


* Monthly trends (~14% dip in sales in Sept-Oct from peak) and top and bottom-selling pizzas.<br />


* These insights can help to increase Average Order Value by 15% and reduce wastage of bottom selling pizzas by 10%.<br />

## Dashboard :
![PBI Pizza Dashboard](https://github.com/shripadk1999/Project_Pizza_Sales_Analysis_Using_SQL/assets/161477229/7fcc4dfc-954e-4f8a-866a-b1bfb9050e31)
![PBI Pizza Sales Report](https://github.com/shripadk1999/Project_Pizza_Sales_Analysis_Using_SQL/assets/161477229/0cbd1e94-bc38-44db-87b0-4cdf0e0d7fb1)

**Shripad Kulkarni**  
- Email: [shripadkulkarni2212@gmail.com](mailto:shripadkulkarni2212@gmail.com)  
- LinkedIn: [Shripad Kulkarni](https://www.linkedin.com/in/shripad-kulkarni-candoit)  
- GitHub: [Shripad Kulkarni](https://github.com/shripadk1999)
