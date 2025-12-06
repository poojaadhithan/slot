# Ex03 Time Table
## Date:6.12.2025
## Ref No:25003349

## AIM
To write a html webpage page to display your slot timetable.

### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="#a5fc03">
<caption><b>SLOT TIME TABLE - POOJA A (25003349)</b></caption>
<tr align="center">
<th bgcolor="#03befc">Day/Time</th>
<th bgcolor="#03befc">Monday</th>
<th bgcolor="#03befc">Tuesday</th>
<th bgcolor="#03befc">Wednesday</th>
<th bgcolor="#03befc">Thursday</th>
<th bgcolor="#03befc">Friday</th>
</tr>
<tr align="center">
<th bgcolor="#03befc">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="#03befc">10-12</th>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>EDM</td>
<td>EDM</td>
<td>EDM</td>
</tr>
<tr>
<th bgcolor="#03befc">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="#03befc">1-3</th>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="#03befc">3-5</th>
<td>FREE SLOT</td>
<td>MATHS</td>
<td>MATHS</td>
<td>MATHS</td>
<td>EDM</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>MATHS</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>EDM</td>
</tr>
~~~


## OUTPUT


![alt text](<Screenshot 2025-12-06 110432.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
