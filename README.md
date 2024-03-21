# Ex03 Time Table
## Date:21-03-24

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
   <title> TIME TABLE </title>
   <body>
   <center>
    <img src="/static/logo.png"height="100"width="540">
<table border="6" bgcolor="cyan" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE - kolluru pujitha (23002983) </caption>

<tr bgcolor="blue">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> SATURDAY </th>
</tr>
<tr align="center">
   <th bgcolor="red"> 8-10 </th>
   <td> FREE SLOT</td>
   <td> FREE SLOT </td>
   <td> CHEMISTRY </td>
   <td> OPERATING SYSTEM </td>
   <td> FWAD </td>
   <td> PROBABILITY </td>
</tr>
<tr align="center">
    <th bgcolor="red"> 10-12 </th>
    <td> BEEE</td>
    <td> FWAD </td>
    <td> FREE SLOT</td>
    <td> PROBABILITY </td>
    <td> C PROGRAMMING </td>
    <td> CHEMISTRY </td>
</tr>
<tr align ="center">
    <th bgcolor="red"> 12-1 </th>
    <td colspan="5" align="center"> LUNCH </td>
</tr>
<tr align ="center">
    <th bgcolor="red"> 1-3 </th>
    <td > FREE SLOT </td>
    <td> PHYSICS </td>
    <td> PHYSICS</td>
    <td> BEEE </td>
    <td>FREE SLOT</td>
    <td> FREE SLOT </td>
</tr>
<tr align ="center">
    <th bgcolor="red"> 3-5 </th>
    
<td>  C PROGRAMMING </td>
    <td> FREE SLOT</td>
    <td> FWAD </td>
    <td> FREE SLOT </td>
    <td> OPERATING SYSTEM </td>
    <td> FREE SLOT </td>
</tr>
</tr>
</table>
<br>
<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td> 1. </td>
<td> 19AI414 </td>
<td> FWAD </td>
</tr>
<tr align="center">
<td> 2. </td>
<td> 19CS405 </td>
<td> OPERATING SYSTEM </td>
</tr>
<tr align="center">
<td> 3. </td>
<td> 19MA222 </td>
<td> PROBABILITY </td>
</tr>
<tr align="center">
<td> 4. </td>
<td> 19CY205 </td>
<td> Principles of Chemistry in Engineering  </td>
</tr>
<tr align="center">
<td> 5. </td>
<td> 19EE305 </td>
<td> BEEE </td>
</tr>
<tr align="center">
<td> 6. </td>
<td> 19PH214 </td>
<td> Physics for Quantum Computing </td>
</tr>
<tr align="center">
<td> 7. </td>
<td> 19AI304 </td>
<td> C PROGRAMMING </td>
</tr>
</html>
```

## OUTPUT
![Screenshot 2024-03-21 223808](https://github.com/KolluruPujitha/slot/assets/150231340/e9d5cba0-5edf-4ce8-a367-731bf5006dfb)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
