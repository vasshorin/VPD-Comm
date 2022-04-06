---
layout: default
title: Schema setup
nav_order: 4
---

# Customization
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Overview

This section will introduce how to create a new schema, set it up in your workbench, and add a new table to it.


## Setting up
1. Click on create a schema to see this window. You can name it anything you want. For our purpose, I will name it UserGuide.
![first images](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/first.png?raw=true)

2. Click **Apply** at the bottom right corner.
![second image](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/second.png?raw=true)

3. In the pop-up window, do not modify the algorithm or lock type, and click **Apply**. 
![third image](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/third.png?raw=true)

4. In the following windown, press **Close**.

5. After you press close, in the left menu right click on your schema and choose **Set as Default Schema**.
![fifth](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/fifth.png?raw=true)

6. In the top menubar, press the **File** tab -  **New Query Tab**. This will open a new window with an empty query field.
![sixth](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/sixth.png?raw=true)

``````*Note* To make sure that it works, you can do the following steps by creating a table.

1. In the empty window, type 

```
CREATE TABLE `UserGuide`.`Persons` (
    PersonID int,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
);
```

This will create a table called Persons in your schema. (Note if you used different name for schema, you need to replace `UserGuide` with your used name).
![seven](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/seventh.png?raw=true)

2. Press execute sign (lightning bolt) to run executable code.
![eigth](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/eighth.png?raw=true)

3. In order for it to appear at the right part of the menu, you need to refresh your database. Right-click on your newly created schema > **Refresh All**

![nine](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/nineth.png?raw=true)

4. You now should be able to work in the created table and see it in your menu like that
![ten](https://github.com/vasshorin/VPD-Comm/blob/Gh-pages/assets/images/tenth.png?raw=true)

## Conclusion

Now that you know how to create, set up, and initilaze schema, you should be able to work with queries and table. Please proceed to the following section to learn how to manipulate data.








