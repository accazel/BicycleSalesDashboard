<h1>Bicycle Sales Dashboard (Excel)</h1>

<h2>Description</h2>
Project consists of transforming a simple Excel dataset into a graphical user interface using the following steps: <br />
 ✅ Data Importing: importing data into Microsoft Excel <br />
 ✅ Data Cleaning: cleaning and processing the data<br />
 ✅ Data Manipulation: using various techniques to shape the dataset for data analysis and visualization <br />
 ✅ Data Visualization: displaying the data using charts and graphs
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Excel</b> 

<h2>Walk-through:</h2>

<p align="center">
 Data Importing: <br/>
 Started with the raw dataset, ready for cleaning <br/>
<img width="967" alt="Screen Shot 2023-09-19 at 1 46 31 PM" src="https://github.com/accazel/BicycleSalesDashboard/assets/8965854/cedb656c-9c71-4c8b-978c-21172fda1750">
<br />
<br />
 Data Cleaning:  <br/>
 Identified and deleted any duplicate rows. There were 26 duplicate rows. <br/>
 Added a filter to the header. Reviewed each header for any typos or errors that may affect dashboard. <br/>
 Marital Status - Filtered & Replaced "S" & "M" with clearer alternative "Single" & "Married" <br/>
 Gender - Filtered & Replaced "F" & "M" with clearer alternative "Female" & "Male" <br/>
 Income - Confirmed data type was currency. Rounded to nearest whole number. <br/>
 Age Brackets - Added new column "Age Brackets" to group age by 3 groups to make filtering easy later on. =IF(L9>54,"Old",IF(L9>=31,"Middle Age",IF(L9<31,"Adolescent","Invalid")))<br/>
<img width="1013" alt="Screen Shot 2023-09-19 at 1 55 16 PM" src="https://github.com/accazel/BicycleSalesDashboard/assets/8965854/963b5f21-0ed8-4f6f-93ae-bdbebe78d883">

<br />
<br />
 Data Manipulation:  <br/>
Created pivot tables and corresponding charts within the "Pivot Table" tab <br/>
<img width="658" alt="Screen Shot 2023-09-19 at 2 07 18 PM" src="https://github.com/accazel/BicycleSalesDashboard/assets/8965854/9b9aa324-5ac3-4177-b91a-b69c810f67f7">

<br />
<br />
Data Visualization:<br/>
Copied over charts from the previous tab. Added slicers to allow users to filter the data reflected in all charts.  <br/>
<img width="920" alt="Screen Shot 2023-09-18 at 3 30 18 PM" src="https://github.com/accazel/BicycleSalesDashboard/assets/8965854/09df0a8d-f9db-44cb-b2ae-59b20e9708d4">
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
