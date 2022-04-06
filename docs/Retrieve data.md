---
layout: default
title: Retrieve data
nav_order: 5
---

# Retrieving data

In SQL, we use the SELECT keyword to retrieve data. The general syntax is as follows;

![Select syntax](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add7.png?raw=true)

From the figure above, box 1 shows how to select specific column names from the table. Box 2 shows how to select all columns from the table. Although declarative, order is also important in retrieving data in SQL. 
The general order is as follows.

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add8.png?raw=true)

Hence, following the example in the figure above, we can retrieve data. 
To select everything in the Persons table we use the *. 
Try to run the following command:

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add9.png?raw=true)

The following table will be shown in the result grid. 

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add10.png?raw=true)

Now lets try to query data based on conditions. 
Lets say we want to retrieve rows of data for people only from the city of Avondale. 

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add11.png?raw=true)

From the image, the underlined statement shows how we add that condition. 
We can try other conditions like persons whose id is greater than 2. 

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add12.png?raw=true)

The following results appear in the result grid.

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add13.png?raw=true)

Furthermore, in addition to just specific rows, we can also query specific columns.

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add14.png?raw=true)

We can specify the order of the columns and can even create an alias of the column name. Here is another example.

![Select order](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/add15.png?raw=true)

Congratulations, you have learned how to retrieve data using basic queries. 








