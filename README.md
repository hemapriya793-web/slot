# Ex03 Time Table
## Date:20.09.2025

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
    <head>
        <title align="center">SLOT TIMETABLE-HEMAPRIYA S (25017270)</title>
    </head>
    <body>
        <img scr="logo.png" height="100" width="750">
        <table border="3" cellspacing="2" cellpadding="10" bgcolor="pink">
        <caption><b>SLOT TIME TABLE-HEMAPRIYA S(25017270)</b></caption>   
        <tr bgcolor="yellow">
            <th bgcolor="yellow">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr bgcolor="pink">
            <th bgcolor="yellow">8-10</th>
            <td align="center">FWAD</td>
            <td>FWAD</td> 
            <td>ENG</td>
            <td>C PROGRAM</td>
            <td>FWAD</td>
        </tr>
        <tr bgcolor="pink">
            <th bgcolor="yellow">10-12</th>
            <td>FREE SLOT</td>
            <td>ENG</td>
            <td>ENG</td>
            <td>FREE SLOT</td>
            <td>ENG</td>
        </tr>
        <tr bgcolor="pink">
            <th bgcolor="yellow">12-1</th>
            <td colspan="6" align="center">LUNCH BREAK</td>
        </tr>
        <tr bgcolor="pink">
            <th bgcolor="yellow">1-3</th>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>MENTOR-MEET</td>
            <td>C PROGRAM</td>
            <td>ENG</td>
        </tr>
        <tr bgcolor="pink">
            <th bgcolor="yellow">3-5</th>
            <td>C PROGRAM</td>
            <td>C PROGRAM</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>C PROGRAM</td>
        </tr>
    </table>
    <table border="3" cellspacing="5" cellpadding="10">
        <tr>
            <th><b>S.NO</b></th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">4L2-1</td>
            <td>Fundamentals of web application development(FWAD)</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">4L2-2</td>
            <td>Communicative English(ENG)</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">4L3-3</td>
            <td>C program(C PROGRAM)</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">ECA-M</td>
            <td>Mentor meet(MENTOR-MEET)</td>
        </tr>
    </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (24).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
