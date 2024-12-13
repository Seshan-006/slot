# Ex03 Time Table
## Date:13.12.2024

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
        <title>
            slot name
        </title>
    </head>
    <body  text="maroon">
        <center>
        <img src="C:\Users\admin\slot\riya\slotapp\static\logo.png" height="100" width="500">
        
        <table border="3" cellpadding="10" cellspacing="10" width="800" >
            <caption align="centre">slot time table-ODD JUNIOR</caption>
            <TR bgcolor="silver">
                <TH>-</TH>
                <TH>MONDAY</TH><TH>TUESDAY</TH><TH>WEDNESDAY</TH><TH>THURSDAY</TH><TH>FRIDAY</TH><TH>SATURDAY</TH>
            </TR>
            <tr>
                <td>8-9am</td>
                <td >-</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td bgcolor="aqua">Engineering Design and Modeling</td>
                <td>-</td>
                <td bgcolor="aqua">calculus and matrix algibra</td>
                <td>-</td>
            </tr>
            <tr>
                <td>10am-12pm</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
                <td bgcolor="aqua">communicative english</td>
                <td bgcolor="aqua">Digital electronic</td>
                <td bgcolor="aqua">calculus and matrix algebra</td>
            </tr>
            <tr>
                <td>12pm</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>1-3pm</td>
                <td bgcolor="aqua">human values and proffessional ethics</td>
                <td bgcolor="aqua">communicative english</td>
                <td bgcolor="aqua">Mentor Meet</td>
                <td bgcolor="aqua">c programming </td>
                <td bgcolor="aqua">c programming</td>
                <td bgcolor="aqua">Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>3-5pm</td>
                <td>-</td>
                <td >-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
        </table>
        <table border="5" cellpadding="5" cellspacing="5" width="1000">
            <tr>
                <td>SH7801</td>
                <td>human values and proffessional ethics</td>
            </tr>
            <tr>
                <td>19AI302</td>
                <td>Engineerin Desing and Modelling</td>
            </tr>
            <tr>
                <td>19AI414</td>
                <td>Fundamentals of Web Application and Development</td>
            </tr>
            <tr>
                <td>19AI304</td>
                <td>c programming</td>
            </tr>
            <tr>
                <td>19EE404</td>
                <td>Digital electronic</td>
            </tr>
            <tr>
                <td>ECA-M-SCOFT</td>
                <td>Menotr Meet</td>
            </tr>
            <tr>
                <td>19EN101</td>
                <td>communicative english</td>
            </tr>
            <tr>
                <td>19MA201</td>
                <td> calculus and matrix algebra</td>
            </tr>
        </table>
    </center>
    </body>
</html>
'''

## OUTPUT

![Screenshot (78)](https://github.com/user-attachments/assets/73846a2e-a0f5-47f6-a443-57128f7f6bf4)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
