# Ex02 Time Table
## Date:19-05-2026

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
'''
<html>
    <head>
        <title>slot Timetable</title>
    </head>
    <body>
        <center>
        <img src="c:\Users\acer\Downloads\saveethapic.jpeg "height="200" width="800">
        </center>
        <br>
        <table align="center" width="600" cellspacing="2" cellpadding="4" border="6" bgcolor="pink">
            <caption><b>SLOT TIME TABLE: R.DEEPIKA</b></caption>
            <tr align="center">
                <th bgcolor="red">Time/Day</th>
                <th bgcolor="red">Monday</th>
                <th bgcolor="red">Tuesday</th>
                <th bgcolor="red">Wednesday</th>
                <th bgcolor="red">Thursday</th>
                <th bgcolor="red">Friday</th>
                <th bgcolor="red">Saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="red">8-10</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>python programming</td>
                <td>python programming </td>
                <td>python programming</td>
                <td>Free slot</td>
            </tr>
            <tr align="center">
                <td bgcolor="red">10-12</td>
                <td>python programming</td>
                <td>Web</td>
                <td>Web</td>
                <td>Free slot</td>
                <td>web</td>
                <td>Free slot</td>
            </tr>
            <tr align="center">
                <td bgcolor="red">12-1</td>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>
            <tr align="center">
                <td bgcolor="red">1-3</td>
                <td>Free slot</td>
                <td>Web</td>
                <td>Mentor Meet</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</td>
            </tr>
            <tr align="center">
                <td bgcolor="red">3-5</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</td>
            </tr>
            </table>
            <br>
            <table align="center" cellspacing="2" cellpadding="4" border="6">
            <tr align="center">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamentals of web application development</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI301</td>
                <td align="center">python programming</td>
            </tr>
            
            <tr>
                <td align="center">3.</td>
                <td align="center">ECA-M</td>
                <td align="center">Mentor Meet</td>
            </tr>
            </table>
        </body>
    </html>
    '''

## OUTPUT

![alt text](<Screenshot 2026-05-19 124442.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
