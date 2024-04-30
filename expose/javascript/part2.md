1. At line 12, 3 is returned since that is the length of the array of prices which the for loop goes through and as it goes through element in prices it will add 1 to i.
2. Code will return 150 since it goes through each price in the prices array and the last element is 300 which with the discount is 150 so it is last set to 150.
3. Code returns 150 since it is last set to 150 nsince 300 is the last price that is discounted so finalPrice rounds the number before pushing it so will return 150.
4. Function will return an array with all prices in prices array but with the discount applied.
5. Code would cause an error since i is not defined since it is only defined within a block of code due to let.
6. Code would return an error since discountedPrice with let is only defined for the for loop since let only allows the vriable to be set for that block of code.
7. Code would return 150 since finalPrice is defined through let in the beginning and therefore will apply for the entire block of code.
8. Code would return the array of discounted prices since discounted is defined in the beginning of the function therefroe the entire block of code is the function.
9. An error would occur since i is not defined and let was used to define i so is only defined in the for loop.
10. 3 will be returned since length is a set ariable that doesn't change and is not resaasigned.
11. Will return the array of discounted prices since const is an array that is only added the prices but not changed.
12. Given the above Object, write the notation for:
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher']
    5.  student.courseLoad[0]
13. Arithmetic
    1.  '32' since it will concatenate the string '3' witht he number2
    2.  1 since subtractions is not defined for strings so will perform the operation
    3.  3 since null is treated as 0
    4.  '3null' since the addition will concatenate 3 with null
    5.  4 since it will true as 1
    6.  null since false is treated as 0
    7.  '3undefined' will concatenate the string '3' with the string 'undefined'
    8.  NaN since subtraction is not defined for strings
14. Comparisons
    1.  true since 2 will be converted to a number
    2.  false since both are strings so comparison will be performed lexicographically.
    3.  true since '==' will convert operands to same type
    4.  false since they are not the same type which '===' has strict equality comparisons
    5.  false since true is treated as 1
    6.  Boolean(2) would return true so comparison is also true
15. '===' has a more strict equality comparison since '==' will convert both operands to the same type while '===' will not
17. The result of this function is [2,4,6] since modifyArray first gets the length of the array [1,2,3] which has a length of three. Then the for loop takes the array length and goes through the each element of the array starting with index 0 to 2. As each number is pushed to the newArr doSomething is called where the returned number is double the original number and therefore the number pushed to newArr is the double which results with [2,4,6].
19. In this code, we can expect the output 1, 4, 3, 2 since console log will output 1 then the setTimeout will delay the output of 2 for a second and 3 is placed in a queue to be returned next so 4 immediated gets returned followed by 3 and 2.