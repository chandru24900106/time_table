# Ex03 Time Table
# Date:
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
<!DOCTYPE html>
<html>
    <head>
       <title>time table </title>
    </head>
    <center>
    
    </center>
    <style>
      table{
        background-color: violet;
        color: black;
        text-align: center;
        padding: 20px;

      }
    </style> 

    <body bgcolor="white">
      <center>
        <img src="saveetha.png" alt="logo">
        <br>
        <br>
        <br>
        <hr>
        <br>
        <br>
        <br>
        <h1 style="color:black";>SLOT TIME TABLE - CHANDRU(24900106) 📅 </h1>
          <table border="5">
            <tr>
                <th>days/time</th> <th>8 to 10</th> <th>10 to 12</th> <th>1 to 3</th> <th>3 to 5</th>

            </tr>
            <tr>
              <td>monday</td> <td>-</td> <td>web application</td> <td>BEEE</td> <td>-</td>
            </tr>
            <tr>
              <td>tuesday</td> <td>english</td> <td>-</td> <td>mathamatics</td> <td>-</td>
            </tr>
            <tr>
              <td>wednesday</td><td>mathamatics</td> <td>chemistry</td> <td>mentor meeting</td> <td>BEEE</td>
            </tr>
            <tr>
              <td>thursday</td> <td>EDM</td> <td>-</td> <td>web application</td> <td>-</td>
            </tr>
            <tr>
              <td>friday</td> <td>english</td> <td>chemistry</td> <td>yoga</td> <td>-</td>
            </tr>
            <tr>
              <td>saturday</td> <td>EDM</td> <td>career development</td> <td>-</td> <td>web development</td>
            </tr>
          </table>
          <br>
          <br>
          <br>
          <table border="5">
            <tr>
              <th>s.no</th> <th>subject code</th> <th>subject name</th>
            </tr>
            <tr>
              <td>1.</td> <td>19MA211</td> <td>statistics and numerical methods</td>
            </tr>
            <tr>
              <td>2.</td> <td>19AI302</td> <td>engineering designing and modelling</td>
            </tr>  
            <tr>
              <td>3.</td> <td>19AI414</td> <td>fundamentals of web application development</td>
            </tr> 
            <tr>
              <td>4.</td> <td>19CY205</td> <td>priciple of chemistry in engineering</td>
            </tr>
            <tr>
              <td>5.</td> <td>19EN101</td> <td>communicative english</td>
            </tr>
            <tr>
              <td>6.</td> <td>19EE305</td> <td>basic electrical,electronics and measurement engineering</td>
            </tr>
          </table>
        </center> 
    </body>
</html>
```
# OUTPUT
![Screenshot 2024-12-07 155253](https://github.com/user-attachments/assets/ff54808d-765a-4db3-ba2e-e616e89bcb65)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
