**Question 1:**
At line 12, console.log(i) will print 3. This is prices.length is 3 and the indexing variable i will be incremented accordingly in the for-loop. 
It is still accessible at line 12 because i was declared as a "var" which means it does not go out of scope.

---

**Question 2:**
At line 13, the value 150 is printed out. This is computed within the body of the for loop on the last iteration. Since "discountedPrice" was declared as a var, it does not go out of scope when the for loop terminates.

---

**Question 3:**
var finalPrice does not go out of scope. Therefore there are no errors when the print statement is run. This statement will print 150, because that is the final price calculated in the last iteration of the for loop.

---

**Question 4:**
This function will return an array containing [50, 100, 150]. This is because the function returns discoutned which is declared as an empty array, and within the for loop we take the current prices, calculate the discounted price and then push those price to discounted.

---

**Question 5:**
This will result in a reference error. The variable i was declared within the  for loop conditions using "let." Therefore once the for loop terminates the variable will go out of scope and the console.log(i) will not know what i is.

---

**Question 6:**
Likewise, discountedPrice  is declared within the body of the for loop using let. Therefore it goes out of scope once the for loop ends. LIne 13 will have  a reference error because it doesn't know what discountedPrice is.

---

**Question 7:**
This will print 150. This is the value calculated in the last iteration of the for loop.  Unlike the preivous two questions, finalPrice was declared within the body of the function not within the for loop so at line 14, the variable is still in scope. Thus, the variable is accessible and can be printed properly.

---

**Question 8:**
The function will return an array containing the discounted prices: [50, 100, 150]. These are the values calculated in the for loop by doing 
```
    finalPrice = Math.round(discountedPrice * 100)/100;
```
And then pushing that to the array discounted. This is the variable that is being returned.

---

**Question 9:**
On line 11 we will have the same error as in question 5. The variable i within the for loop is still declared with let, and therefore once the for loop terminates the variable goes out of scope and the line of code on line 11 does not know what the variable i is. This is a reference error.

---

**Question 10:**
The code will correctly output 3. The length variable was declared within teh body of the function, and the line 12 is also within the body of the function. There are no scope errors, and t he value assigned to the variable is equal to the length of the input array prices which is 3 because we inputted 3 numbers.

---

**Question 11:**
This will return the same th ing as before: an array containing [50, 100, 150]. This is calculated within the body of the for loop and then added to discounted using discounted.push. Since the variable was not reassigned there are no errors even though discounted is a const.

---

**Question 12:** (this apparently is supopsed to be in part2.md)

```
    student.name;                       // part a
    student["Grad year"];               // part b
    student.greeting();                 // part c
    student["Favorite Teacher"].name    // part d
    student.courseLoad[0]               // part e
```

---

**Question 13:"**
- Part a prints 32. This is because '3' is type string and the 2 is concatanated to it.
- Part b prints 1. The '3' is numerically converted into the number 3 and then 2 is subtracted from it
- Part c prints 3. Through numeric conversion rules, null becomes 0.
- Part d prints 3null. This is because '3' is a string and it concatenates with null which is treated as a string.
- Part e prints 4. This is because the boolean treue is numerically converted to the value 1, 1 + 3 = 4
- Part f prints 0. False is numerically converted to 0. Null is numerically converted to 0. 0 + 0 = 0
- Part g prints 3undefined. '3' is treated as a string and undefined gets concatenated to it.
- Part h prints NaN. This is because when you do numeric conversions, undefined is converted to NaN and therefore the result of the subtration is also NaN

---

**Question 14:**
- Part a prints true. '2' is numerically converted to 2. And 2  is greater than 1 returns true.
- Part b prints false. '2' is compared to '12' and they are both strings, it looks at the first digit and '1' is actually greater than '2' becaues it is  alphabetically first.
- Part c prints true. The '2' string gets numerically covnerted because it is being compared with a number. 2 == 2 is true.
- Part d prints false. === is doing a strict equality without doing type conversion. Since they are different types, the two operands are not the same
- Part e prints false. true is numerically converted to 1 and 1 is not equal to 2.
- Part f prints true.  Doing boolean(2) will be return a true boolean. True is already a true boolean, so they are the same in terms of value and type.

---

**Question 15:**
The difference between == and === lies in the fact that === is strict equality which means that if the two operands are different types they are not equal. With == you can do some type conversion before comparing because it is weakly typed.

---

**Question 16:**
> This is on part2-question16.js

---

**Question 17:**




