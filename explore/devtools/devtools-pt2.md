**Question 1**
The bug is that num1 and num2 are strings.
THe line of code let num1 = document.getEleemtnById("num1").value; will assign num1 a string value.
When you add two strings it will concatenate them rather than adding their numerical value. 
The final result is a string as well.


**Question 2**
In order to fix the bug, you need to explicily turn num1 and num2 into numbers by doing numeric conversion explicitly.
