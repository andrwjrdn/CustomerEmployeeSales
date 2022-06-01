# CustomerEmployeeSales

In this project, I grabbed a large Sales dataset online that had multiple tables with a relationship model. What I wanted to show in this project was to create a report of Sales and Profits within the dataset. 

![image](https://user-images.githubusercontent.com/44654955/171493641-e4c34315-df91-4a95-bf68-dc275358ce46.png)

In the image above is the relationship model that was mostly already set up with the dataset I used. 


To find the data I needed I had calculate certain measures with DAX formulas such as <b> Total Sales, Total Cost, Total Profit, and the Profit Margin </b> from the products table. 

<li>To calculate Total Sales, I used the SUMX function of grabbing all sales from the sales table and multiplying it by price.</li> 
<li>For the Total Cost of Products I used another SUMX function and multiplied sales quantity with the Product Cost.</li>  
<li>I then subtracted the Total Sales minus the Total Cost number to find my Total Profit.</li> 
<li>By dividing the Total Profit and Total sales, I was able to get the profit margin % of each product and total sales.</li>
<br></br>
<br></br>
I then used the these measures to display a report via Power BI Dashboard


![image](https://user-images.githubusercontent.com/44654955/171495774-809d13c3-b095-4aeb-b1c0-95d200a9e500.png)
