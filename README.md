# Ex03 Time Table
# Date:24/09/2025
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
<thead>
                <html>
    <head>
        <style>
           .a th {
                background-color: yellow;
            }
           .a td {
                background-color: aqua;
            }
        </style>
    </head>
    <body>
        <center>
        <img src="/static/logo.png">
        <br><br>
        <div class="a">
        <table border="4" bgcolor="aqua">
            <caption>SLOT TIME TABLE - S.SANJAY (25017293)</caption>
            <thead>
                <tr>
                    <th>Date/Time</th>
                    <th>8-10</th>
                    <th>10-12</th>
                    <th>12-1</th>
                    <th>1-3</th>
                    <th>3-5</th>
                </tr> 
            </thead>
            <tbody>
                <tr><th>Monday</th><td>FWAD</td><td>Free slot</td><td rowspan="6">Lunch</td><td>C Programming</td><td>Free slot</td></tr>
                <tr><th>Tuesday</th><td colspan="2">Com.English</td><td colspan="2">Free slot</td></tr>
                <tr><th>Wednesday</th><td colspan="2">FWAD</td><td>Mentor meeting</td><td>C Programming</td></tr>
                <tr><th>Thursday</th><td>Com.English</td><td>C Programming</td><td>Com.English</td><td>C Programming</td></tr>
                <tr><th>Friday</th><td>C Programming</td><td>FWAD</td><td colspan="2">Free slot</td></tr>
                <tr><th>Saturday</th><td>Com.English</td><td>FWAD</td><td>Com.English</td><td>Free slot</td></tr>
            </tbody>
        </table>
        </div>
        <br>
        <table border="1">
            <caption>Subject List</caption>
                <tr>
                    <th>S.NO.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
            </thead>
            <tbody>
                <tr><th>1.</th><td>19AI414</td><td>FWAD</td></tr>
                <tr><th>2.</th><td>19AI304</td><td>C Programming</td></tr>
                <tr><th>3.</th><td>19EN414</td><td>Com.English</td></tr>
            </tbody>
        </table>
        </center>
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-09-24 092644.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
