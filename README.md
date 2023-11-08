# Ex03 Time Table
## Date: 08.11.2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
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
```
<html>
<title>Time Table</title>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<center>
<table border="2" cellspacing="2" cellpadding="6" bgcolor="cyan">
<caption>SLOT TIME TABLE- THAKSHA RISHI (23013212)</caption>
<tr>
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">8-10</th>
	<th bgcolor="yellow">10-12</th>
	<th bgcolor="yellow">1-3</th>
	<th bgcolor="yellow">3-5</th>
</tr>
<tr>
	<th bgcolor="yellow">Monday</th>
	<td>English</td>
	<td>Chemistry</td>
	<td>Free Slot</td>
	<td>Physics</td>
</tr>
<tr>
	<th bgcolor="yellow">Tuesday</th>
	<td>English</td>
	<td>Python</td>
	<td>Chemistry</td>
	<td>Free Slot</td>
</tr>
<tr>
	<th bgcolor="yellow">Wednesday</th>
	<td>FWAD</td>
	<td colspan="2" align="center">Free Slot</td>
	<td>Python</td>
</tr>
<tr>
	<th bgcolor="yellow">Thursday</th>
	<td>Free Slot</td>
	<td>FWAD</td>
	<td>Free Slot</td>
	<td>Python</td>
</tr>
<tr>
	<th bgcolor="yellow">Friday</th>
	<td>Python</td>
	<td>Physics</td>
	<td>FWAD</td>
	<td>Free Slot</td>
</tr>
</table>
<br>
<table border="2" cellspacing="2" cellpadding="6">
<tr>
	<th align="center">S.No</th>
	<th align="center">Subject Code</th>
	<th align="center">Subject Name</th>
</tr>
<tr>
	<td align="center">1.</td>
	<td>19AI414</td>
	<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
	<td align="center">2.</td>
	<td>19AI301C</td>
	<td>Python and Linear Algebra</td>
</tr>
<tr>
	<td align="center">3.</td>
	<td>19EN101</td>
	<td>Communicative English</td>
</tr>
<tr>
	<td align="center">4.</td>
	<td>19CY205</td>
	<td>Principles of Chemistry in Engineering</td>
</tr>
<tr>
	<td align="center">5.</td>
	<td>19PH214</td>
	<td>Physics in Quantum Computing</td>
</tr>
</table>
</center>
<br>
</body>
</html>
```


## OUTPUT
![Alt text](time.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
