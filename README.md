# Ex02 Time Table
## Date:21.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
slot.html

<html>
<head>
<title>My Time Table</title>
</head>

<body>

<img src="logo.png" width="400" height="100">

<h2 align="center">SLOT TIME TABLE - SANGAVI A(26017697)</h2>

<table border="5" cellpadding="14" cellspacing="3"
bgcolor="violet" align="center">

<tr bgcolor="purple">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>

<tr>
<th bgcolor="purple">8-9.30</th>
<td>Comp Arch</td>
<td>Com Eng</td>
<td>-</td>
<td>-</td>
<td>Comp Arch</td>
<td>Python</td>
</tr>

<tr>
<th bgcolor="purple">9.45-11.15</th>
<td>Calculus</td>
<td>Com Eng</td>
<td>-</td>
<td>Python</td>
<td>-</td>
<td>FWAD</td>
</tr>

<tr>
<th bgcolor="purple">11.15-1.15</th>
<td colspan="6" align="center">
L U N C H
</td>
</tr>

<tr>
<th bgcolor="purple">1.15-2.45</th>
<td>-</td>
<td>Calculus</td>
<td>-</td>
<td>Career Dev</td>
<td>FWAD</td>
<td>FWAD</td>
</tr>

<tr>
<th bgcolor="purple">3-4.30</th>
<td>Digi Elec</td>
<td>-</td>
<td>Python</td>
<td>-</td>
<td>Digi Elec</td>
<td>-</td>
</tr>

</table>

</table>

    <br>

    <table border="2" cellpadding="8" cellspacing="1" align="center">

        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>

        <tr>
            <td>2.</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>

        <tr>
            <td>3.</td>
            <td>19CS305</td>
            <td>Computer Architecture</td>
        </tr>

        <tr>
            <td>4.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>

        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra </td>
        </tr>

        <tr>
            <td>6.</td>
            <td>19AI301</td>
            <td>Python</td>
        </tr>

    </table>



</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (29).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
