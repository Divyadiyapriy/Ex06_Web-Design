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
~~~
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
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~


## OUTPUT
![sub-1 ](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/62366fa0-d827-476e-8d7e-2b6aa81d53e5)
![sub-2](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/a7184645-5d93-45de-be37-67723f096719)
![sub-3](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/69ccb7b7-6ece-4f93-9f03-4ab3ca406532)
![sub-4](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/6c16f753-57b6-4561-b969-05f02746f2a3)
![sub-5](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/bc11a0ca-1690-46c3-8303-dd378248a78d)
![result](https://github.com/Divyadiyapriy/Ex06_Web-Design/assets/127817268/c8ca88be-17cd-4e95-8d4f-bb2a10af2b3f)






## RESULT
  Student result using JavaScript is created successfully.
