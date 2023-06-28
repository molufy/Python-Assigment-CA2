# Python-Assigment-CA2
 Second assigment

CA guideline :


Read in the below information of a company’s transactions for the year 2022 into a python dictionary files.

a. Convert each database into a dataframe in python.

b. Note that the databases and the corresponding column names with spelling differences. Correct this to have all column names without ‘s’

dbase1
TR_ID
Product
Quantitys
Purchase_prices
C23
Telephone
420
223
C24
Monitors
Ten
344
C25
Car
234
223
C26
Rent
114
Tenn
C27
Services
56
Two
C28
Training
13
223

dbase2

TR_ID
Products
Sale_price
Debit
C23
Telephone
300
2
C24
Monitors
435
2
C25
Car
329
2
C26
Rent
544
2
C27
Services
thirty
2
C28
Training
329
2


dbase 3
TR_ID
Product
Quantity
Purchase_price
Sale_price
C28
Training
13
223
329


c. Combine the above three databases into one single dataframe called ‘dbase4’ in python using the appropriate method and libraries.

d. Consider the character values as error, remove these errors and replace with column’s mean.

e. Delete the variable ‘Debit’ as not needed then add a column called ‘Department’ and assign values from product column: 
Telphone, monitor -> IT, 
Car -> transport
Rent, Services-> Consultancy
Training -> Education
 
f. Visualise the data by creating the plot: product by sale and purchase prices on the same plot.

g. After creating the single dataframe:

Using Object and Class method with the above corrected values:  

In the function section of your class and object method program:

Calculate:

Revenue = Quantity*Sale_price 
Cost= quantity*purchase_price

Note if revenue > $55000 then a cashback of 5% is given so revenue is less by the 5% amount
If revenue > $35000 and <= $550000 then cashback of %2 is given and revenue less the 2% amount
But If revenue <=35000 then cashback of 1% amount is given

The calculated total cost and total revenue 

Profit= total revenue – total cost.

Report the TR_ID, product name, total revenue , total cost and profit.
Check if final profit> 0 then print a message.
If final profit =0 then print a message
If final profit < 0 then print a message 
