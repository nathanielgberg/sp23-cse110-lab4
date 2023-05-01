1. The bug was when you add the first and second numbers together it concatenates them as strings instead of subtracting them as integers. This is because they are not integers which is why it is giving the wrong result.
2. To fix this bug you would cast the strings as int so you would do parseInt on num1 and num2 which would fix the issue and add them together as integers.
