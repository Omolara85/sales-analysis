# Godswill Enterprise Sales Analysis

### Table of contents

- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Tools](#tools)
- [Data Analysis](#data-analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Limitation](#limitation)

### Project Overview
***

This data set project to provide insights in to the sales performance of Godswill enterprise. By analyzing various aspect of revenue, identify the season revenue, gender contribution to Godswill enterprise and make recommendation

![Screenshot (4)](https://github.com/user-attachments/assets/5b3b7e66-8e4e-4705-9913-049b65fe10c2)


### Data Source

sales data: the data set use for this analysis is "Sales Data set.Excel File", contain information of the company records for their sales, and this data set was provided by Quantum Analysis NG 

### Tools

- Excel - Data cleaning
-  [Download here](https://microsoft.com)
  
### Data Cleaning/Preparation

in this data cleaning some functions are use to bring out another row of data in the table.
the functions are IFS function and TEXT function;
- IFS function is use to create the Age group on the table and also for the Season.
- TEXT function is use fro separating the weeks name, month name and years from the date in the table.
- subtraction.
- mutiplications.

### Exploratory Data Analysis

Godswill Enterprise involve exploring the sales data to answer key question;

 - Season with highest profit.
 - Gender contribution to revenue.
 - Age group that contributed most to the business in terms of revenue.
 - Annual performance.
 - Daily profit trend.
 - Top 10 Sub-category with the most profit.
   
### Data Analysis  

Include some interesting code/functions worked with

'''Excel
 - =IFS([@Month]="December","Winter",[@Month]="January","Winter",[@Month]="February","Winter",[@Month]="March","Spring",[@Month]="April","Spring",[@Month]="May","Spring",[@Month]="June","Summer",[@Month]="July","Summer",[@Month]="August","Summer",[@Month]="September","Fall",[@Month]="October","Fall",[@Month]="November","Fall")
 - =TEXT([@Date],"DDDD")
 - =[@Revenue]-[@[Total Cost]]
 - =[@[Unit_Price]]*[@[Order_Quantity]]

   ### Result/Findinds
    Data set Summary
   - Spring Season always has the highest profit yearly.
   - Aldult contribute more revenue to the enterprise.
   - Road Bikes is the best selling product

   ### Limitation

   I have to subtract Revenue from Total ccost to get my Profit and also mutiply Unit price with Order quantity to get my total cost.

   ### Reference
    - Zoom video on linkedin by zainab omolara OLUWO
    - [Linkedin](https://www.linkedin.com/posts/zainab-oluwo-774a89304_as-an-intern-at-quantum-analytics-ng-im-activity-7209871915392421888-Qzql?utm_source=share&utm_medium=member_desktop)
   
