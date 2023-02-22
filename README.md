# AmazingMart Sales Analysis in Tableau
## Data Source
- [P1-AmazingMartEU2.xlsx](https://github.com/CelineWW/AmazingMart_Tableau/blob/main/P1-AmazingMartEU2.xlsx)

## Results and Tableau Visualizaions
### Donut KPI
- Use Dummy and dual axis to create donut chart.
- Sales by Category slightly different from regions.
![KPI Donut Chart](https://user-images.githubusercontent.com/105877888/220547814-628539a9-b867-4534-9f97-ede3af0fa995.png)

### Hierarchical LOD Map
- Use LOD(label of Details) and `Include`, `Fixed`, `Exclude` to label hierarchical Map.
- France sales the most in Europe.

![LOD Dual Map](https://user-images.githubusercontent.com/105877888/220548058-a5afaf0d-c8dc-4553-9168-840f265fa682.png)

![LOD Hierachical Chart](https://user-images.githubusercontent.com/105877888/220548081-abdcca2d-0cc3-45a1-a200-4ead1d2f932e.png)

### WaterFall Chart
- Use gantt bar chart and negative values to create waterful chart
- Second half of years has more sales than the first half of years.

![Waterfall Sales Chart](https://user-images.githubusercontent.com/105877888/220548346-5bff3f93-3356-4cb9-9820-b299a7ee597e.png)

### Dual Line Chart
- Use dual axis to combine sales and profit chart.
- Overall, sales in 2011-2013 is less than 2014-2015. However, profit in in 2011-2013 is more than 2014-2015.
![Profit and Sales](https://user-images.githubusercontent.com/105877888/220548252-750e35bb-9104-4997-899c-615466f6c509.png)

### Area + Line Chart
- Combine line chart and area chart to get highlight area edge.
- At the beginning of years, sales typically run low.
- Profit distributed evenly.

![Sales Area Chart](https://user-images.githubusercontent.com/105877888/220548452-bbc25ba2-6886-434a-aa42-33391b31f9e9.png)


![Profit Area Chart](https://user-images.githubusercontent.com/105877888/220548482-f2396dfd-645c-4204-be6b-918b13f0a066.png)

### Sub-Category Pareto Chart
- Use bar chart, line chart with runing sum of sales to create pareto chart. 
- Bookcases, Copies, Phones, Storage, Appliances, Chairs accumulated 80% of Total Sales.

![Sales Pareto Chart](https://user-images.githubusercontent.com/105877888/220548626-6d222bc8-4195-4a6b-bfed-71d01f5a05ba.png)

### Chart with Data Blending
- Add data sources to blend the data on common cloumns(or change column names to link) to compare target and actrural sales.
- Furniture sales doesn't meet the target very well. Office Supplies sales mostly beyond the expectation. Technology sales changes over the months, overall it fulfills the target sales of the year. 
![Sales Fullfillment Bar Chart](https://user-images.githubusercontent.com/105877888/220548749-be6c6a02-55c1-40e2-bec9-2f8769289526.png)


![Sales Fullfillment Area Chart](https://user-images.githubusercontent.com/105877888/220548789-39e98685-9a6b-4e18-93c1-981d9f4f82f4.png)

### Dashboard 
- Dashboard to organize the worksheets together.
![AmazingMart Dashboard](https://user-images.githubusercontent.com/105877888/220548843-95292c15-0cd4-46f6-b018-377ecb1018e2.png)
