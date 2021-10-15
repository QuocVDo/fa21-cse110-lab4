# Part 1 

**Question 1:** 
Line 9 will print "values added: 20"

**Question 2:**
Line 13 will print "final result: 20"

**Question 3:**
Line 9 will print "values added: 20"

**Question 4:**
Line 13 will have a reference error. This is becacuse the "let" keyword declared the variable inside of the if statement which means it goes out of scope after the if statement. Line 13 does not have access to the result variable.

**Question 5:**
Line 9 will be an error because result is a const, which means you can't reassign its value. const result was initally set to 0. So it can't be reassigned.

**Question 6:** 
Line 13 will be an error because const has the same scope as let, so by the time we get to line 13, the result variable will have gone out of scope.
