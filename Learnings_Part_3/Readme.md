# Learnings Part 3 Includes : 

## 1) Conditional Columns : 

Create new columns using the columns in the table. Steps for it are mentioned in the .pbix file. Follow the steps and create meaningful columns to get meaningful visuals out of it. 

Also Data modeling is also included in it. Connect Unique keys to make models. One of the best ways to take insights from, of what these tables indicate.

## 2) Operations

## 3) Functions

## 4) DAX Functions :

Data Analysis Expressions (DAX) is a library of functions and operators that can be combined to build formulas and expressions in Power Bi.
DAX formulas are used in measures, calculated columns and calculated tables.

### DAX Function

How to do it in Power Bi ???

Follow the steps :

#### Modeling --> New Column
Go to the "Data" section on the left side of the screen and add the new column and make the necessary additions. 

#### The query used is given at the top of the bar.

![Screenshot (81)](https://user-images.githubusercontent.com/98825618/205233708-bdd18e4d-2150-4e18-8bec-ace1128bd492.png)
![Screenshot (82)](https://user-images.githubusercontent.com/98825618/205234810-d7a8d436-5cb5-4b67-81bf-7891e2f30856.png)
![Screenshot (83)](https://user-images.githubusercontent.com/98825618/205236367-38a724f9-2887-4191-9108-ab9fcb297d91.png)

You can see that we have added 3 new and diffrent columns using DAX functions. 

First column is the "Sqrt-sales" second is the "Power-sales" and third is the "Round figure value of the Sqrt-sales" column up to 2 digits. you can also check out other ROUND functions in Power Query Editor i.e MROUND, ROUNDDOWN(rounds up to the previous digit), ROUNDUP(rounds up to the next digit) etc.

The Power Query editor is smart enough to do all the calculations for you and generate the result for you. You can also see the queries written for each column creation.

Now we will calculate the "Cost Price" and the "Profit Percentage"(%) in the set using DAX functions or Arithematic operators. 

![Screenshot (84)](https://user-images.githubusercontent.com/98825618/205274750-203b1bff-4211-4e5b-8808-cddf382f63e8.png)
![Screenshot (86)](https://user-images.githubusercontent.com/98825618/205276313-52c504af-2b50-44c9-9798-f76245b0189f.png)

Till Now we saw some of the arithematic DAX functions and basic formula based DAX functions like Cost Price and Profit Percentage.
There are many formulas which can be used on many diffrent datasets based on the requirements and on what you want to achieve.

Next Up is the "Date and Time" DAX functions. Let's see how can we make them work on our data set and take insights from the results we get.
Date and Time functions are very important in terms of Business, so DAX functions on this becomes really important. So just check it out on how to approach it.

Functions used here are :

DAY, MONTH, DATEDIFF, WEEKDAY, IF/ELSE 

![Screenshot (88)](https://user-images.githubusercontent.com/98825618/205279618-7a440177-eaa8-41cc-98f3-fa332ce10acf.png)
![Screenshot (87)](https://user-images.githubusercontent.com/98825618/205279664-58f4b159-15a3-4730-99a2-8ac05edfbf9c.png)
![Screenshot (89)](https://user-images.githubusercontent.com/98825618/205280215-e8caa006-1316-4b22-b5d7-71c6aafde73c.png)
![Screenshot (90)](https://user-images.githubusercontent.com/98825618/205282220-2e843925-0e1f-4ef9-acd4-83f5eb946da3.png)
![Screenshot (92)](https://user-images.githubusercontent.com/98825618/205428105-27b3eee7-238a-49c8-9c0f-b62f2933bcc9.png)

So after doing all the necessary addition of the DAX functions as per requirements, we next are going to make some visuals out of the created columns.
Just like the one I am adding down. We can create many such meaningful visuals as and when required and put it up in the dashboards.

![Screenshot (91)](https://user-images.githubusercontent.com/98825618/205289753-1d047a94-df8e-4e13-8de3-5c89a0186ecd.png)





