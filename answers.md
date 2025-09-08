The file creates a table with ID, name, domain and way of propulsion. Columns are ID, name, domain and propulsion. INT and VARCHAR. INT is integer and VARCHAR can be letters and numbers and store 255. INT can store 2 147 483 647. 
AUTO_INCREMENT makes it so that the nr in ID adds one everytime a new row is created. 

- get_data.php 
<?php
?>
For opening and closing. 

For creating variables:
$VARIABLENAME = "WHAT VARIABLE IS"

The variables are our servername, username, the password for the user and the name of the database. 

$link = mysqli_connect($servername, $username, $password, $dbname); 
Seems to be a way to connect the server to a database in mysql. 
Line 10-12 seems to represent what happens when the server cant connect to the database. 

Echo seems to be like a print for the web browser which can read this as html code. 

A table where table head is ID Name Domain Propulsion. 

$link seems to help import and connect all "animals" in the animals column in SQL. 
-> is to call the method query

We are acessing in SQL the rows that exist. The if statements makes it so does the query return more than 0 rows. Then it fetches row by row from the sql database and prints(echos) it in the HTML format. If there are no rows then it says 0 results. 

I think the file gets the data for the table of animals on the website form an sql server. 

insert_data.html
A form is a place where a user can input data. 

insertdata.php

SLut