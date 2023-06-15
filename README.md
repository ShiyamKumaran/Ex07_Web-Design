# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```


## OUTPUT
![Screenshot 2023-06-11 044216](https://github.com/ShiyamKumaran/Ex07_Web-Design/assets/127816458/339dba36-d75e-44e6-b0b9-a31cf628b47e)
![Screenshot 2023-06-11 044255](https://github.com/ShiyamKumaran/Ex07_Web-Design/assets/127816458/dfa2af94-e713-4839-abdf-8ebde89d18b6)
![Screenshot 2023-06-11 044325](https://github.com/ShiyamKumaran/Ex07_Web-Design/assets/127816458/adab8748-90a2-4750-b56b-454f1ac176fd)
![Screenshot 2023-06-11 044353](https://github.com/ShiyamKumaran/Ex07_Web-Design/assets/127816458/2f8b12ab-c9d6-42a8-8d15-886e6e49e007)
![Screenshot 2023-06-11 044427](https://github.com/ShiyamKumaran/Ex07_Web-Design/assets/127816458/6b022c4e-de35-474c-8274-a46a1d45a67f)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
