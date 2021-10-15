**Question 1:**
At line 12, console.log(i) will print 3. This is prices.length is 3 and the indexing variable i will be incremented accordingly in the for-loop. 
It is still accessible at line 12 because i was declared as a "var" which means it does not go out of scope.

**Question 2:**
At line 13, the value 150 is printed out. This is computed within the body of the for loop on the last iteration. Since "discountedPrice" was declared as a var, it does not go out of scope when the for loop terminates.

**Question 3:**
var finalPrice does not go out of scope. Therefore there are no errors when the print statement is run. This statement will print 150, because that is the final price calculated in the last iteration of the for loop.

**Question 4:**
This function will return an array containing [50, 100, 150]. This is because the function returns discoutned which is declared as an empty array, and within the for loop we take the current prices, calculate the discounted price and then push those price to discounted.

**Question 5:**
This will result in a reference error. The variable i was declared within the  for loop conditions using "let." Therefore once the for loop terminates the variable will go out of scope and the console.log(i) will not know what i is.

**Question 6:**
Likewise, discountedPrice  is declared within the body of the for loop using let. Therefore it goes out of scope once the for loop ends. LIne 13 will have  a reference error because it doesn't know what discountedPrice is.

**Question 7:**
This will print 150. This is the value calculated in the last iteration of the for loop.  Unlike the preivous two questions, finalPrice was declared within the body of the function not within the for loop so at line 14, the variable is still in scope. Thus, the variable is accessible and can be printed properly.

**Question 8:**
The function will return an array containing the discounted prices: [50, 100, 150]. These are the values calculated in the for loop by doing 
```
{
    finalPrice = Math.round(discountedPrice * 100)/100;
}
```
And then pushing that to the array discounted. This is the variable that is being returned.

**Question 9:**
On line 11 we will have the same error as in question 5. The variable i within the for loop is still declared with let, and therefore once the for loop terminates the variable goes out of scope and the line of code on line 11 does not know what the variable i is. This is a reference error.

**Question 10:**
The code will corredcty output 3. The length variable was declared within teh body of the function, and the line 12 is also within the body of the function. There are no scope errors, and the value assigned to the variable is equal to the length of the input array prices which is 3 because we inputted 3 numbers.

**Question 11:**
This will return the same th ing as before: an array containing [50, 100, 150]. This is calculated within the body of the for loop and then added to discounted using discounted.push. Since the variable was not reassigned there are no errors even though discounted is a const.

**Question 12:** (this apparently is supopsed to be in part2.md)
