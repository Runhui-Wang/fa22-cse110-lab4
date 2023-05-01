1. What will happen at line 12 and why? If the code causes an error, explain why.
- The length of the array is 3. Thus the returned value will be 3 as the loop will run for length of the array times. 
2.  What will happen at line 13 and why? If the code causes an error, explain why. 
- 150.
3. What will happen at line 14 and why? If the code causes an error, explain why.
- 150
4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
- [50,100,150]
5. What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
- It will cause error since i is not defined in scope. 
6.  What will happen at line 13 and why? If the code causes an error, explain why. 
- Error. This variable is undefiend in scope. 
7. What will happen at line 14 and why? If the code causes an error, explain why.
- 150. Calculated value and defined in scope. 
8. What will this function return? Give a brief explanation. If the code causes an error, explain why.
- [50,100,150]defined in scope. 
9. What will happen at line 11 and why? If the code causes an error, explain why. 
- It will cause error since i is not defined in scope. 
10. What will happen at line 12 and why? If the code causes an error, explain why. 
- The length of the array is 3. Thus the returned value will be 3
11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
- [50,100,150]defined in scope.
12. Given the above Object, write the notation for:  (These should be in your part2.md)
- Accessing the value of the name property in the student object: student.name
- Accessing the value of the Grad Year property in the student object: student["Grad Year"]
- Calling the function for the greeting property in the student object: student.greeting()
- Accessing the name property of the object in the Favorite Teacher property in student: student.["Favorite Teacher"].name
- Access index zero in the array of the courseLoad property of the student object: student.courseLoad[0]
 13. Arithmetic:
'3' + 2 output: "32". Explanation: The + operator concatenates the string "3" with the number 2, resulting in the string "32".
'3' - 2 output: 1. Explanation: The - operator attempts to subtract the number 2 from the string "3". Since the string cannot be subtracted from a number, JavaScript automatically converts the string to a number and performs the subtraction, resulting in the number 1.
3 + null output: 3. Explanation: The + operator attempts to add the number 3 and the value null. When null is coerced to a number, it becomes 0. Thus, the expression evaluates to 3.
'3' + null output: "3null". Explanation: The + operator concatenates the string "3" with the string representation of null, resulting in the string "3null".
true + 3 output: 4. Explanation: When a boolean value is coerced to a number, true becomes 1 and false becomes 0. Thus, the expression evaluates to 4.
false + null output: 0. Explanation: When a boolean value is coerced to a number, false becomes 0. Thus, the expression evaluates to 0.
'3' + undefined output: "3undefined". Explanation: The + operator concatenates the string "3" with the string representation of undefined, resulting in the string "3undefined".
'3' - undefined output: NaN. Explanation: The - operator attempts to subtract the value undefined from the string "3". Since undefined cannot be converted to a number, the expression evaluates to NaN (Not a Number).

14. Comparison:
'2' > 1 output: true. Explanation: When comparing a string to a number, JavaScript converts the string to a number. Thus, the expression evaluates to 2 > 1, which is true.
'2' < '12' output: false. Explanation: When comparing strings, JavaScript compares their Unicode code points character by character. Thus, the expression evaluates to '2' < '1', which is false.
2 == '2' output: true. Explanation: The == operator performs type coercion, so it converts the string "2" to the number 2 before comparing. Thus, the expression evaluates to 2 == 2, which is true.
2 === '2' output: false. Explanation: The === operator performs strict comparison without type coercion, so it compares the string "2" and the number 2 as different types. Thus, the expression evaluates to 2 === '2', which is false.
true == 2 output: false. Explanation: The == operator performs type coercion, so it converts true to 1 before comparing. Thus, the expression evaluates to 1 == 2, which is false.
true === Boolean(2) output: true. Explanation:  Boolean(2) is true. However, since === performs strict comparison, it compares a boolean and a number as different types. Thus, the expression evaluates to true === true, which is true

15. Explain the difference between the == and === operators.
- The == operator performs type coercion, which means it tries to convert both operands to a common type before comparing them. On the other hand, the === operator performs strict comparison without type coercion, 

16. Given the above Object, write a for...in loop that will iterate through it and print out the value of the property if the property starts with the letter r, or if the value of that property is an odd number.  (This should be in a JS file part2-question16.js)

17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result. (This should be in your part2.md). Here we are passing in a function as a parameter, however we can also return a function from another function just as easily, you're encouraged to play around with callbacks as they are used heavily in frontend JS development. 
- [2,4,6] Each of the element in the array passed will be called doSomething and doubled. Going through the array and update the new array. 

18. The above program only prints out the time once when executed. Modify this code such that the program prints out the time every second.  (This should be a JS file - part2-question18.js)

19. What is the output of the above code? (This should be in your part2.md) 