# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![Screenshot (10)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/dc293f2b-8d74-4cb5-b7c6-471d0e539d33)
![Screenshot (11)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/0e65824c-e597-4ef6-8dca-3a9d0fe09b07)
![Screenshot (12)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/cdbca617-49f8-46e6-a443-c497c9f98432)
![Screenshot (13)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/b95ce00e-b547-4184-8c1c-3fc414bdcbfa)
![Screenshot (14)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/45d35308-df1e-4cdf-9af5-d43c62f6901c)
![Screenshot (15)](https://github.com/prishapradeep/Ex06_Web-Design/assets/166732237/0465e573-b1cb-4e4d-97b9-94eb434d90c9)







## RESULT
  Student result using JavaScript is created successfully.
