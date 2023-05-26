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
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
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



## OUTPUT
![Screenshot 2023-05-26 222115](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/ab667d0a-7a50-472e-9cb3-650a206c3542)
![Screenshot 2023-05-26 222130](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/309cc9b7-ed18-42fb-a02b-8c0bbd1e9687)
![Screenshot 2023-05-26 222142](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/714a54ad-e6d6-4e94-9e4a-da8a225c9c42)
![Screenshot 2023-05-26 222154](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/d18462b8-58ce-47b7-821c-b0ff79d36208)
![Screenshot 2023-05-26 222007](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/49c1ec4c-19a6-44b9-9d10-d0d1ad689d8c)
![Screenshot 2023-05-26 222028](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/c725a970-a3e6-447e-8abf-b06c19faf71d)
![Screenshot 2023-05-26 222049](https://github.com/Akshayaprabha/Ex06_Web-Design/assets/127816387/9cc58941-a0d2-4fcd-b80d-a1fcbd27c089)


## RESULT
  Student result using JavaScript is created successfully.
