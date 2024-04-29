1. Line 9 should produce "values added:  20".
2. Line 13 should print "final result:  20".
3. Line 9 prints "values added:  20".
4. Line 13 returns an error because it is trying to access the variable "result", but because it is defined in the "if" block, it doesn't exist outside that scope. Therefore, line 13 is referencing a variable thst no longer exists (defined) and causes the error. 
5. The code returns an error before line 9 when (at line 7) because since result is set to a constant, it cannot be reassigned to be the sum of num1 and num2.
6. The code returns an error before line 13 when (at line 7) because since result is set to a constant, it cannot be reassigned to be the sum of num1 and num2.