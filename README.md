# Ex03 Time Table

## DATE
07-10-2023

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
<html>
<head>
    <title>SLOT TIME TABLE - HARISH G (23000630)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        th, td {
            border: 5px solid #000000;
            text-align: center;
            padding: 8px;
        }
    </style>
</head>
<body>
<style>
    .center-text {
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="center-text">
  <img src="logo.png" class="center-image" width="1200" height="150">
    <p>SLOT TIME TABLE - HARISH G(23000630)</p>
  </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">SS</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
    </table>
</body>
</html>




<table border="1">
  <tr>
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
  </tr>
  <tr>
    <td>1</td>
    <td>19A1414</td>
    <td>Fundamentals of Web Application Development (FWAD)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>19PH206</td>
    <td>Physics for Information Technology (PHY)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>19CY205</td>
    <td>Principles of Chemistry in Engineering (CHE)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>19MA201</td>
    <td>Calculus and Matrix Algebra (MAT)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>19EY701</td>
    <td>Soft Skills (SS)</td>
  </tr>
</table>
```
## OUTPUT
![image](https://github.com/Harish2404lll/slot/assets/141472096/cb83abf2-a80d-4135-8349-8565395a6bf7)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
