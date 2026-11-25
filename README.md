# Ex02 Time Table
## Date:23/11/2026

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
<html>
    <head>
        <title>My Timetable</title>
    </head>
<body>
<center>
    <img src="c:\Users\acer\Downloads\lakshika.png" height="100" width="700">
    <h2>SLOT TIME TABLE - Lakshika S (26019050)</h1>
    <table border="4" cellpadding="7" cellspacing="2" width="700" bgcolor="lavender">
       <tr bgcolor="pink">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
       </tr>
       <tr>
        <th bgcolor="skyblue">8:00-9:30</th>
        <td bg color="lime">CA</td>
        <td>CDS</td>
        <td>Cyber</td>
        <td>DE</td>
        <td>Statistics</td>
        <td>Python</td>
       </tr>
       <tr>
        <th bgcolor="skyblue">9:45-11:15</th>
        <td>DE</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>Statistics</td>
        <td>FREE SLOT</td>
        <td>FWAD</td>
       </tr>
       <tr>
        <th bgcolor="skyblue">11:30-12:15</th>
        <td>Mentor Meet</td>
        <td>LUNCH</td>
        <td>MentorMeet</td>
        <td>Free Slot</td>
        <td>Mentor Meet</td>
        <td>Mentor Meet</td>
       </tr>
       <tr>
        <th bgcolor="skyblue">12:15-1:00</th>
        <td> LUNCH</td>
        <td>MENTOR MEET</td>
        <td>LUNCH</td>
        <td>LUNCH</td>
        <td>LUNCH</td>
        <td>LUNCH</td>
       </tr>
       <tr>
        <th bgcolor="skyblue">1:15-2:44</th>
        <td>FREE SLOT</td>
        <td>Cyber</td>
        <td>FREE SLOT</td>
        <td>CA</td>
        <td>FWAD</td>
        <td>FWAD</td>
       </tr>
       <tr>
        <th bgcolor="skyblue">3:00-4:30</th>
        <td>EDM</td>
        <td>EDM</td>
        <td>Python</td>
        <td>CA</td>
        <td>PYthon</td>
        <td>FREE SLOT</td>
       </tr>
    </table>
    <br><br>
    <table border="2" cellpadding="7" width=80%>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td>1.</td>
            <td>19AI50</td>
            <td>Fundamentals Of Web Application And Development</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI60</td>
            <td>Python</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CSE834</td>
            <td>Cyber Law</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19ODJ831</td>
            <td>Statistics And Numerical Methods</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CSE761</td>
            <td>Computer Architecture</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EEE002</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19ODJ345</td>
            <td>Career Development And Skills</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>26ODJ321</td>
            <td>Mentor Meet</td>
        </tr>
    </table>
</center>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (73).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
