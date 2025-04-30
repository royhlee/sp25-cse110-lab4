1\. The bug is that the data type for result is a not a number but a string which ends up having string concatenation occur.
2\. To fix it I would assign num1 and num2 to be of the data type Number.