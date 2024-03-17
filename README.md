Task Description: 
I Created a basic web application that allows user to  enter input,store it in database and I created a html table for display the user enterd the input in the same page. 

1.	Programming Language Used:PHP and for designing  used CSS.


2.	User Input Form:
  •	Created a web form that includes fields for the following data:
  •	Name (text input)
  •	Email (email input)
  •	Age (number input)
  •	Date of Birth (date input)

   For validtion of name i used required value attribute this attribute automatically tells the field and i used[A-Z][a-z] pattern that tells to user to enter only Alpahabets and it is started with Capital only.
  For email i used input type as email this input type automatically remind the user to enter a valid email,
  For age i used minimum,maximum values and minimum start with 1 so this indicates that user to only enter a positive number or value.
  For date used required attribute.
  
  I used CSS for Styling.

If enterd input is valid then Registration successsful alert pop is dipalyed. After successfull registration data is stored in database.

 Database is connection is created using :
  server:localhost
  username:root
  password:""
  database:stu

  
   
3.	Database:
 I used XAMP and in XAMP control panel apache and mysql both are stated. After starting the sever i created data base.
 The DataBase name is stu.
 The Table name is tt with 5 coloumns.
 1. Name:id, Type:int
 2.Name:name,Type:varchar
 3.Name:email,Type:varchar
 4.Name:age,Type:varchar
 5.Name:date,Type:varchar
table is created successfully.

The User entered input is stored in database.

  
4.	Data Retrieval:
•	Created a html table to store database data(or) fetch the data from database in html table.
The retrieval data is displayed in same page.

This is the WebApplication I created.
 


