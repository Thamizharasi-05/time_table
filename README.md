# Ex03 Time Table
# Date:01.04.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
<html>
<head>
<title>Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="magenta">
    <caption><b>TIME TABLE - G THAMIZHARASI  (212224100059)</b></caption> -
    <tr align="center">
        <th bgcolor="purple">Day/Time</th>
        <th bgcolor="purple">Monday</th>
        <th bgcolor="purple">Tuesday</th>
        <th bgcolor="purple">Wednesday</th> 
        <th bgcolor="purple">Thursday</th>
        <th bgcolor="purple">Friday</th>
        <th bgcolor="purple">saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="purple">8-10</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="purple">10-12</th>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
    </tr>
    <tr>
        <th bgcolor="purple">12-1</th>
        <td colspan="6" align="center" bgcolor="lavender">L U N C H</td>
    </tr>
    <tr align="center">
        <th bgcolor="purple">1-3</th>
        <td>FREE SLOT </td>
        <td>FREE SLOT</td>
        <td>MENTOR MEETING</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr align="center">
        <th bgcolor="purple">3-5</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
        <td>FREE SLOT</td>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
        <td>FREE SLOT</td>
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
        <td align="center">19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>
    <tr>
        <td align="center">2.</td>
        <td align="center">19AI304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
    </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center">19EE305</td>
        <td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center">19AI302</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19CY205 </td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19MA211</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19HS801</td>
        <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
    </tr>
</table>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-04-03 101631.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
