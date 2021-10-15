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
