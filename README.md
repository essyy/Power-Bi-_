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
iris_id <- setDt(iris_id, keep.rownames= TRUE)[] ( Keep rownames (optional)
setnames(iris_id, 1,"id")  ( Rename the first column to "id")
iris_id$id <- as.integer(iris_id$id)  (Convert the "id" column to integer (if necessary)
