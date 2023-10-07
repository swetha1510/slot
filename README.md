# Ex03 Time Table

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

## CODE
```
<!DOCTYPE html>
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<img src="logo.png" width='600'align='center'>
<body>
    <table BORDER='3' width='600'bgcolor='cyan' cellspacing='3'>
        <CAPTION align="above">SLOT TIMETABLE-SWETHA (22008542)</CAPTION>
        <tr>
            <th align="center" bgcolor="yellow">Day/Time</th>
            <th align="center" bgcolor="yellow">Monday</th>
            <th align="center" bgcolor="yellow">Tuesday</th>
            <th align="center" bgcolor="yellow">Wednesday</th>
            <th align="center" bgcolor="yellow">Thursday</th>
            <th align="center" bgcolor="yellow">Friday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">8-10</th>
            <td align="center" bgcolor="cyan" colspan="3">FREE SLOT</td>
            <td align="center" bgcolor="cyan">PHY</td>
            <td align="center" bgcolor="cyan">CHE</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">10-12</th>
            <td align="center" bgcolor="cyan">GER</td>
            <td align="center" bgcolor="cyan">FREE SLOT</td>
            <td align="center" bgcolor="cyan">FWAD</td>
            <td align="center" bgcolor="cyan">FWAD</td>
            <td align="center" bgcolor="cyan">PHY</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">12-1</th>
            <td align="center" bgcolor="cyan" colspan="5">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">1-3</th>
            <td align="center" bgcolor="cyan" colspan="2">FREE SLOT</td>
            <td align="center" bgcolor="cyan">MAT</td>
            <td align="center" bgcolor="cyan">MAT</td>
            <td align="center" bgcolor="cyan">SS</td>
        </tr>


        <tr>
            <th align="center" bgcolor="yellow">3-5</th>
            <td align="center" bgcolor="cyan" colspan="2">FREE SLOT</td>
            <td align="center" bgcolor="cyan">GER</td>
            <td align="center" bgcolor="cyan">CHE</td>
            <td align="center" bgcolor="cyan">FWAD</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3">
c

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19EN612</td>
            <td align="center">German Basics(GER)</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19PH206</td>
            <td align="center">Physics for Information Technology</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19CY205</td>
            <td align="center">Principal of Chemistry in Engineering(CHE)</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19MA201</td>
            <td align="center">Calculus and Matrix Algebra(MAT)</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19EY701</td>
            <td align="center">Soft Skills(SS)</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![image](https://github.com/swetha1510/slot/assets/120623583/f2c3c42a-6000-45ec-a36a-2ad5cd122a10)


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
