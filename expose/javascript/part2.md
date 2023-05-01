1. The value of the variable i will be printed to the console which is 3. After the loop is finished the value of i will be equal to the length of the prices array which is where 3 comes from.
2. The last calculated discounted price is printed which is 150. When it is looping through the array 300/0.5 is the last price it goes through which is 150.
3. The last calculated discounted price is printed which is 150.
4. The function will return an arry [50,100,150] which are the prices after the 50% discount has been applied.
5. At line 12 a ReferenceError will occur because i is declared with let so it is only accessible in the for loop and can't be accessed any where else.
6. At line 13 a ReferenceError will occur because the let discountedPrice is in the for loop so it is not accessible anywhere else.
7. The finalPrice wil be printed which is the new array [50,100,150] after the 50% discount has been applied.
8. The function will return [50,100,150] which are the prices after the 50% discount has been applied. 
9. At line 11 a ReferenceError will occur because i is not defined outside the for loop since it was declared with let. You can't access the variable i.
10. At line 12 the code will log the length of the prices array which is 3 in this case. 3 is logged to the console.
11. This function will return an array [50,100,150] which are the prices after the 50% discount has been applied.
12. 
  a. student.name
  b. student['Grad Year']
  c. student.greeting()
  d. student['Favorite Teacher'].name
  e. student.courseLoad[0]
13. 
  a. '3' + 2 = '32' because string and a number will concatenate them as strings
  b. '3' - 2 = '1'  as the string 3 will be converted to a number 3 and minus 2 which is 1
  c. 3 + null = '3' adding a number to null returns original number
  d. '3' + null = '3null' because null will be the string null and then concatenate together
  e. true + 3 = '4' because true is converted to 1 so 1 + 3 = 4.
  f. false + null = 0 because false is converted to 0 so 0 + null is 0
  g. '3' + undefined = '3undefined' because undefined becomes a string so it concatenates them together
  h. '3' - undefined = 'NaN' because will try to convert the 3 string to a number but it can't so the result is NaN.
14.
  a. '2' > 1 = true because string '2' is converted to a number 2 and then compared to 1 which is true
  b. '2' < '12' = true because the first character '2' is less than the first character '1' so it is true
  c. 2 == '2' = true because the string '2' is converted to a number 2 and compared to 2 which is true
  d. 2 === '2' = false because it is a strict equality comparison making the type of operands different so it returns false
  e. true == 2 = false because true is coerced to 1 and then compared to 2 which false
  f. true === Boolean(2) = false because it is a strict equality comparison so the operands are different so false 
15. The == and === are used for comparison. The == is the equality operator so it compares two values for eqaulity after converting their types. They have to be a common type. The '===' operator is a strict equality that compares two values but unlike == no conversion is done. They must be the same type to be considered equal. 
17. The result will be a new array [2,4,6] because you will multiply each element in the original array [1,2,3] times 2. doSomething is passed as the callback function. Then modifyArray will iterate through the array and apply the doSomething function to each element. Lastly it pushes the changed values to the new array that is returned.
19. The output of the above code is 1 4 3 2
  
