# Power-Bi-_
The first document GDP, and the data is cleaned then the visualization is done to get insights on the countries' GDP. Using this insight, other plans in terms of investments can be made using this information.
## In merging sheets, you should use two unique rows in the instance that the data in them is not the same
- Pivotig can only be done on two columns
## Fact dimension model 
- This makes the operation faster - they are ordered in transaction tables made up of dimensions that are static tables
### Other contexts covered
- Merge cells, create index column, create a column, merge cells
- Cardinality data and how to choose based on the data which one suits the project 
- Use of tables to carry out the calculations including COUNT(DISTINCT) etc which will be used to obtain the data, don't summarize etc
- difference between visualization tools and the use of tables
- the table, one can be also able to edit
- The mode of aggregation can be changed in the value setting
- every data in the table can be formatted using conditional formatting
- select setting to show just the bars
- visuals iN data using symbols on the charts
- Pie charts - used for showing a percentage (Most commonly used ) Only use it if there is 100%
- Tooltips is used to give additional information
- use of slicers to filter the year data
- ![image](https://github.com/user-attachments/assets/b0e45bbb-c4cf-4f26-9918-047a97200dc7)
in visualization when creating slicers, the filter pane after the visualizations pane, should be used to filter the blanks and null sections in the slier. There are three types of filtering namely:
* Basic filtering - normal
* Advanced filtering
* ![image](https://github.com/user-attachments/assets/f46b41d3-99e4-4fdc-bd23-9a6e0b5db662)
* Top N - top values
  - how to change the slicer - horizontal 
- Removing interactions between the visualization, highlight or filter
- ### Syncing the slicers in different pages-- use the sync slicers section to enable both pages to have th filter activated
- The advanced filter enables the settings to be adapted immediately for syncronisation 
- ### Drill down enables one to zoom within the regions
- Expand all down enables the data to be narrown b etter than drill
- #### Drill through -
- ##### treemap - Tree Maps are primarily used to display data that is grouped and nested in a hierarchical (or tree-based) structure. 
- The use of edit interaction determines whether the two tables will have a relation/connection to them
- Decomposition tree -- determine the aggregation data used -- help the user to analyse that data easier
- Matrix table - enables the visuals to be more in depth and informative
- In the editing of the dashboards, deselect the sync slicers
- Use of buttons for animations using action and tootip for a hover on the animation
- ###### in a button, when one chooses bookmark, you can create  a custom button
- ###### To do this, you need to use bookmark and select. The bookmark, you can update it
- line graphs -- if you have two lines, you can use teh secondary value to enable both to be demonstrated
- ![image](https://github.com/user-attachments/assets/e5f90950-b83f-44c7-a2c3-f125c830e9c3)
- using line graphs you can also have the analytica and forecast wich is a prediction
- ## Use of R
- the code is:
iris_id <- iris (# 1. Convert iris to a data.table)
iris_id <- setDt(iris_id, keep.rownames= TRUE)[] ( Keep row names (optional)
setnames(iris_id, 1,"id")  ( Rename the first column to "id")
iris_id$id <- as.integer(iris_id$id)  (Convert the "id" column to integer (if necessary)
* Introduction of gg plot to plot the graph
* ![image](https://github.com/user-attachments/assets/ac00da09-c3b9-425e-bc79-55a019b7caa5)
- use of the second code
- ![image](https://github.com/user-attachments/assets/732a95a2-461c-4851-9f44-f85aa1db3c37)
library(ggplot2)
ggplot(data=dataset,aes(x=Sepal.Width, y=Sepal.Length, color=Species)) + geom_point() + geom_smooth() + theme_minimal()
--##### use of Q&A IN THE r scripts
  ![image](https://github.com/user-attachments/assets/58ffc1ad-8d02-4ac1-9e94-f95d5f3a249d)
### python for Bi 
- Use of plt.plot (datasets needed then, 'go' -- this returns Os the g-- gives lines as output
- statistical analysis, violin chart is used via the seaborn package
- ![image](https://github.com/user-attachments/assets/ac1ac34d-a6e7-4f95-8b97-67b90e3f0437)
- measure and column diff is the measure is a virtual column
- CALENDARAUTO - i is used in determining the automated dates that may be missing based on the dataset
- DAX LANGUAGE to carry out functions such as SUM, COUNT, COUNTROWS, COUNTBLANK, DISTINCTCOUNT, COUNTA, CONTX, COUNTAX
- COUNTA deals with boolean
- 
##### Cloud Gateway 
- to enable constant refreshing opf the published reports, there is need for a gateway
- The steps include: downloading the gateway and connect the Power Bi cloud acount
- In the data source credentials, ensure all is done including signing in
- Get quick installs - creates a summary of the report/dataset
- Creating a dashboard is done via pinning the page or the image
- Workspaces are used to collaborate with other users
- ###### use of mobile layout
- ##### Row level security
- ![image](https://github.com/user-attachments/assets/e4f10c4a-0c66-491b-8968-07d4d1907ba2)
- this enables filtering so that one person can only view what is relevant to tehm
- to do this effectively, it is necessary to ensure there is a both way connection in the table
- use of dynamic  row level security to share a diff visualization based on the email address
- this is done by establishing a security table
- Heirarchical table
- ![image](https://github.com/user-attachments/assets/f0e3aa85-7947-4459-a718-542398ca14a7)

- How to convert a json table to a detailed table
- 
