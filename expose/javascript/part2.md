1. It will print 3, the loop will iterate through 100,200,300 reaching i = 3 printing 3.
2. It will print 150, i will equal 300 since it is in the 2 spot of the array and going through the discountedPrices function it will assign discountedPrice to 150.
3. It will print 150, final price is just the discounted price (150) * 100 then dividing that by 100 printing 150.
4. There will be nothing printed because there is no console.log to print out any values, but there is also no errors.
5. ReferenceError i is not defined, i is defined in the for loop and because let is block scoped after the for loop it cannot be accessed.
6. ReferenceError similar to the last question discountedPrice is only accessible inside of the for loop block.
7. It will print 150, let finalPrice is defined in the function making it function scoped therefore it is able to run through the for loop and give an output.
8. Nothing will be outputted since there is no console.log to print out any values, there are also no errors.
9. ReferenceError i is not defined, let is block scoped therefore i will not be defined outside of the for loop block.
10. It will print 3, the size of the array for prices is 3 and it will count the length of the array.
11. Nothing will be printed because there is no console.log to print out any balues, there are also no errors. <br>
12 A. student.name <br>
12 B. student["Grad Year"] <br>
12 C. student.greeting() <br>
12 D. student["Favorite Teacher"].name <br>
12 E. student.courseLoad[0] <br>
13 A. 32, it is because of string concatenation <br>
13 B. 1, js turns 3 into a number for subtraction <br>
13 C. 3, null becomes 0 so it is 3 + 0 <br>
13 D. 3null, null is now a string and string concatenation makes it 3null <br>
13 E. 4, true is defined as 1 so 1+3 is 4 <br>
13 F. 0, false is defined as 0 and null is defined as 0 so it is 0+0 <br>
13 G. 3undefined, 3 is a string and so is undefined and string concatenation makes it 3undefined <br>
13 H. NaN, undefined cannot be defined as a number therefore the output is not a number <br>
14 A. true, the comparison between 2 and 1 is true, 2 is also defined as a number <br>
14 B. false, comparing the unicode values of 2 and 1 2 is greater than 1 so it returns false <br>
14 C. true, '2' is converted to a number so it compares 2 and 2 <br>
14 D. false, === checks both the value and the type therefore it will return false <br>
14 E. false, true is equal to 1 and 1 does not equal 2 <br>
14 F. true, the boolean value 2 is nonzero which makes it true <br>
15. == compares two values which can also redefine the type to make equality match while, === strictly checks both the value's type and value
17. The output would be [ 2, 4, 6 ], modifyArray takes an array and a callback which then iterates through the for loop and pushes it to the newArr which is returned, doSomething just multiplies a number by 2 which is done to the array which is entered in modifyArray and the new values from doSomething are stored in the new array made in modifyArray.
18. 1 4 3 2