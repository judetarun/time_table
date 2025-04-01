# Ex03 Time Table
# Date:1.04.2025
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
HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>slot timetable</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <center>
        <img src="/static/saveetha.jpg" height="80" width="540">
    </center>
    <h5>CLASS SCHEDULE</h5>
    <table align="center" cellspacing="6" cellpadding="4" border="4"> 
        <tr>
            <th>time</th>
            <th>8 to 9</th>
            <th>9 to 10</th>
            <th>10 to 11</th>
            <th>11 to 12</th>
            <th>12 to 1</th>
            <th>1 to 2</th>
            <th>2 to 3</th>
        </tr>
        <tr>
            <th>monday</th>
            <td colspan="2">ui&ux</td>
            <td colspan="2">EVS</td>
            <td rowspan="6">lunch</td>
            <td colspan="2">math</td>
        </tr>
        <tr> 
           <th>tuesday</th>
            <td colspan="2">CHEM</td>
            <td colspan="2">C programming</td>
            <td colspan="2">EDM</td>
        </tr>
        <tr>
            <th>wednesday</th>
            <td colspan="2">fwad</td>
            <td colspan="2">BEEE</td>
            <td colspan="2">MENTOR MEET </td>
        </tr>
        <tr>
            <th>thursday</th>
            <td colspan="2">fwad</td>
            <td colspan="2">C programming</td>
            <td colspan="2">ui&uX</td>
        </tr>
        <tr>
            <th>friday</th>
            <td colspan="2">BEEE</td>
            <td colspan="2">EDM</td>
            <td colspan="2">CHEM</td>
        </tr>
        <tr>
            <th>saturday</th>
            <td colspan="2">MATH</td>
            <td colspan="2">HUMAN VALUES</td>
            <td colspan="2">FREE TIME</td>
        </tr>

    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="6" border="4" class="table2">
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr> 
            <td>1</td>
            <td>19AI414</td>
            <td>fundamentals of web application development</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI304</td>
            <td>fundamentals of c programming </td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19MA201</td>
            <td>MATHS</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19HS801</td>
            <td>Human values and professional ethics</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19CY205</td>
            <td>PRICIPALS OF CHEMISTRY</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19CS549</td>
            <td>ui & ux design</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19AI302</td>
            <td> ENGINEERING DESIGN AND MODELING</td>
        </tr>

    </table>
    
</body>
</html>
```
CSS
```
body{
    background-color:rgb(152, 184, 192);
}
table{
    width:60%;
    height:300px;
    border:10px solid rgba(50, 102, 193, 0.907);
    border-collapse:collapse;
    margin:auto;
    background-color: rgb(27, 227, 140) ;
}
td{
    border:5px solid rgb(9, 9, 9);
    padding:30px;
    text-align:center;
    font-style:italic;
}
th{
    background-color: #00fff7a1;
    font-style:italic;
    font-weight: 900;
    font-size:large;
}
.table2{
    width:50%;
    height:200px;
    border:10px solid rgba(0, 0, 0, 0.907);
    border-collapse:collapse;
    margin:auto;
    background-color:turquoise;

}
.table2 th{
    background-color:rgb(64, 64, 165);
}
h5{
    font-size: xx-large;
    text-align: center;
}
```
# OUTPUT
![alt text](<Screenshot 2025-04-01 104126.png>)
![alt text](<Screenshot 2025-04-01 104135.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
