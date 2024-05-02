1. The error was that there was no data type checking for the parameters num1 and num2 (to ensure there are not strings or other not a number forms). To fix this we can simply do:
result = parseFloat(num1) + parseFloat(num2) and then return the result.
2. Screenshot uploaded.
