# Ex03 Time Table
## Date:

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
		<title>
			Software Companies
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="yellow">
			<caption>SLOT TIME TABLE- RISHI CHANDRAN R (24900302) </caption>
            <br>
			<tr>
				<th bgcolor="lightgray"> Day/Time </th>
				<th bgcolor="lightgray"> Monday </th>
				<th bgcolor="lightgray"> Tuesday </th>
                <th bgcolor="lightgray"> Wednesday </th>
                <th bgcolor="lightgray"> Thursday </th>
                <th bgcolor="lightgray"> Friday </th>
                <th bgcolor="lightgray"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> WEB </td>
                <td> PQM </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> Free Slot </td>
                <td> CA </td>
                <td> WEB </td>
                <td> PYTHON </td>
                <td> CA </td>
                <td> PYTHON </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> CN </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> Free Slot </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> Free Slot </td>
                <td> WEB </td>
                <td> CN </td>
                <td> PQM </td>
                <td> CD </td>
                <td> QAM </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19CS305 </td>
                    <td align="center"> Computer Architecture(CA) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (WEB) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19MA222 </td>
                    <td align="center"> Probability and Queueing Models (PQM) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19EY708 </td>
                    <td align="center"> Career Development Skill(CD) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19AI301 </td>
                    <td align="center"> Python Porgramming (PYTHON) </td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19EY710 </td>
                    <td align="center"> Quantitative Ability 1 (QA) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19CS406 </td>
                    <td align="center"> Computer Networks (CN) </td>
                </tr>
                
                </table>
	</body>

</html>
```


## OUTPUT


![WhatsApp Image 2024-10-23 at 21 54 45_0261c4d1](https://github.com/user-attachments/assets/c772bf0a-f2a6-4a4c-9aac-f70f97b31e09)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
