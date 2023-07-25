STORED PROCEDURES SHOULD BE CREATED AND USED FOR ALL DATABASE INTERACTIONS
(Submit all stored procedure code in a text file for corrections)

Create the following Table

Products
ProductId int - Primary Key
ProductName varchar(50)
Rate Decimal(18,2)
Description varchar(200)
CategoryName varchar(50)
Populate it with some dummy data.
Create an MVC application with the following Views
(USE APPROPRIATE MODEL WITH PROPERTIES AND METHODS)

1. Index View (10 marks for showing the view correctly, including database code)
Should show all the Products in the following way
``` ProductId ProductName Rate Description CategoryName
101 Harry Porter 10.00 descA Books Edit
102 Percy Jackson 20.00 descB Books Edit
103 Pen 30.00 descC Stationery Edit
104 Marker 30.00 descD Stationery Edit
```

```
2. Edit View (total 8 marks)
( for showing the view correctly -4 marks and updating the database(4 marks))
Product Id ____________ (Display only, not editable)
Product Name ____________ (TextBox)
Rate ____________ (TextBox)
Description _ ___________ (TextArea)
Category ____________ (TextBox)
Update --- (Button)
Back to Index (Hyperlink)
```
```
(3 Marks for a, b and c)
a) Ensure that all values must be entered before submitting them.
b) Give proper error messages for all validations
c) The displayed value in the label should be shown from the annotation for the field. Eg
"ProductName" property should be displayed as "Product Name"
3. Delete View(based on the ProductId delete the product from the table)4 Marks.
Back to Index (Hyperlink).
4. Create your own Layout Page and use this as the default layout page for all Views
Create hyperlinks to take you to your Views.
(Do not use or change the existing _Layout.cshtml page)
(5 marks for Qs No 4)
```
