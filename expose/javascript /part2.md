1. That last value of variable 'i' that comes out of the for-loop structure will get printed out to the console. In this case, it is 3. 
2. The value 150 is printed, as this is the discounted price calculated for price = 300 (last element of the prices array, end of iteration) and discount = 0.5.
3. The value 150 is printed, as this is the final price calculated for the using the discountedPrice for the asscoaited price = 300. In addition, since no keyword was used to declare the variable, javascript treats it as a global variable, so it has scope in the entire file. 
4. This function will return the discounted array which contains the list of discounted price. But since we are not logging anything in the console, we not see an output in the console tab. In addition, there will no error since the discounted variable is declared using let, which provides it function-scope. 
5.  The function results in a "ReferenceError: i is not defined" error. This happens because 'i' is declared using let, which means it's only limited to block-scope. Hence, having being referenced outside of the for-loop, the function throws an error. 
6. The function results in a "ReferenceError: discountedPrice is not defined" error. This happens because 'discoutedPrice' is declared using let, which means it's only limited to block-scope. Hence, having being referenced outside of the for-loop, the function throws an error.  
7. The value 150 is printed, as this is the final price calculated for the using the discountedPrice for the asscoaited price = 300. In addition, since no keyword was used to declare the variable, javascript treats it as a global variable, so it has scope in the entire file. 
8. Similar to question 4, this time also it will return the discounted array which contains the list of discounted price. But since we are not logging anything in the console, we not see an output in the console tab. In addition, there will no error since the discounted variable is declared using let, which provides it function-scope. 
9. The function will throw a "TypeError: Assignment to constant variable" error because after the first iteration of the for loop, due to the const declration of discountedPrice - it does not allow re-assigninment. Hence, in the second iteration of the for loop we get an error. 
10. The length of the array will be printed, which in this case is 3. There will be no error, because there is no re-assignment.
11. Similar to question 4 and 8, this time also it will return the discounted array which contains the list of discounted price. But since we are not logging anything in the console, we not see an output in the console tab. In addition, there will no error event though the discounted variable is declared using const, its reference is never reassigned. 
12. 
    (a) student.name
    (b) student["Grad Year"]
    (c) student.greeting()
    (d) student["Favorite Teacher"].name
    (e) student.courseload[0]

13. 
    Arithmetic 
    (a) '32'
    In Js, the + operator performs concatenation if one of the operands is a string. Here, 2 is coerced to a string and concatenated with '3'.

    (b) 1
    The - operator does not concatenate. It converts the string '3' to the number 3 and subtracts 2, resulting in 1.

    (c) 3
    Null is treated as 0 in numeric contexts, so this expression adds 3 to 0.

    (d) 3null
    Same explanation as (a), but just that '+' concatenates null object with a string, converting the output in string.

    (e) 4
    In numeric contexts, true is treated as 1. Thus, the expression evaluates to 1 + 3.

    (f) 0
    Both false and null are treated as 0 in numeric contexts.

    (g) 3undefined
    undefined is converted to the string 'undefined', and concatenated with '3'.

    (h) NaN
    undefined cannot be converted to a number in a meaningful way, so the result of this subtraction is just not a number. 

14. 
    Comparison
    (a) True
    The string '2' is converted to the number 2 before comparison, and 2 is greater than 1.

    (b) False
    When comparing strings, Js uses lexicographical order. The character '2' comes after '1' in lexicographical order.

    (c) True
    The == operator performs type coercion. Here, the string '2' is converted to the number 2 before comparison.

    (d) False
    The === operator checks both value and type, without coercion. Here, the types (number and string) do not match.

    (e) False
    The == operator does convert operands for comparison, but true is converted to 1, which is not equal to 2.

    (f) 0
    Boolean(2) is true because any non-zero number is evaluated as truth in js. Both operands are of type boolean and both are true.

15. The == operator compares the values of two variables after performing type conversion if necessary. On the other hand, the === operator compares the values of two variables without performing type conversion.

16. Solution in file: "part2-question-16.js".
17. The function will create a new array. Then it will iterate over the input array, and call the doSomething function on each element of the array. In this case, this function just multiplies the element by 2. So the resulting array would have the following elememts: [2, 4, 6].
18. Solution in file: "part2-question-18.js". 
19. The output is going to be: 
    1
    4
    3
    2
    This is because 1 and 4 are printed since there is no delay attached to them, and they get a call from the stack which is cleared first. After that the 3 is printed, even though it's "delayed" by 0 milliseconds, and finally 2 is printed after 1 second. 

