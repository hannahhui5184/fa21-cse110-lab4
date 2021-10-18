# Part 2.
1. The console prints "3" because the value of i after the for-loop will be equivalent to the length of the prices list.
2. The console prints "150" because this is the last discounted price value. (There was a 0.5 discount on a price of 300, which results in a 150 discounted price.)
3. The console prints "150" because this is the last discounted price value rounded to the nearest cent.
4. This function will return a list of discounted prices, [ 50, 100, 150 ], (the discounted prices being in parallel to their respective original prices). This is because in the discountPrices function, we find the discounted price for each element in the list and push it to the list we return.
5. A ReferenceError saying i is not defined is thrown. This is because the scope of i is restricted to inside the for-loop due to the use of the keyword let (and we try to print it outside the for-loop).
6. A ReferenceError saying discountedPrice is not defined is thrown. This is because the scope of discountedPrice is restricted to inside the for-loop due to the use of the keyword let (and we try to print it outside the for-loop).
7. The console will print out "150" because the finalPrice variable has scope throughout the function and this is the value of the last discounted price rounded to the nearest cent.
8. This function will return a list of discounted prices, [ 50, 100, 150 ], (the discounted prices being in parallel to their respective original prices). This is because in the discountPrices function, we find the discounted price for each element in the list and push it to the list we return; and the new list we return is in scope throughout the entire function.
9. A ReferenceError saying i is not defined is thrown. This is because the scope of i is restricted to inside the for-loop due to the use of the keyword let (and we try to print it outside the for-loop).
10. The console prints "3" because this is the length of the prices list. We are able to print this variable because there is no modification of a constant happening.
11. This function will return a list of discounted prices, [ 50, 100, 150 ], (the discounted prices being in parallel to their respective original prices). This is because in the discountPrices function, we find the discounted price for each element in the list and push it to the list we return; and the new list we return is modified with pushing elements but not reassigned another list.

12.    
12A. student.name
12B. student['Grad Year']
12C. student.greeting
12D. student['Favorite Teacher'].name
12E. student.courseLoad[0]

13. 
13A. '3' + 2        ==> '32' because 2 is turned into a string '2' and then concatenated with '3'.
13B. '3' - 2        ==> 1 because there is no - operation for strings, so '3' is turned into a number 3 and 3 - 2 = 1.
13C. 3 + null       ==> 3 because null is turned into a number 0 and then added to 3.
13D. '3' + null     ==> '3null' because null is converted into the string 'null' and concatenated with '3'.
13E. true + 3       ==> 4 because true is converted into a numeric value of 1 and then added with 3.
13F. false + null   ==> 0 because false is converted into a numeric value of 0 and then added with the numeric value of null (which is also 0).
13G. '3' + undefined ==> '3undefined' because undefined is turned into a string 'undefined' and then '3' and 'undefined' are concatenated together.
13H. '3' - undefined ==> NaN because '3' and undefined are converted into numeric values to perform subtraction. Since undefined becomes NaN, any arithmetic operation involving this NaN will result in NaN.

14. 
14A. '2' > 1        ==> true because '2' is converted to a numeric 2 and 2 > 1 is true.
14B. '2' < '12'     ==> false because dictionary-order wise, '1' will come before '2' and therefore '12' should be less than '2'.
14C. 2 == '2'       ==> true because '2' is converted to a numeric 2 and 2==2 is true.
14D. 2 === '2'      ==> false because 2 and '2' are of different types and we are using the strict equality comparator.
14E. true == 2      ==> false because true is converted to a numeric 1 and 1 == 2 is false.
14F. true === Boolean(2. ==> true because Boolean(2. is evaluated to true and true === true is true.

15. The == allows for type conversion of either/both sides and then evaluates the converted types for equality, whereas the === operator will always return false for different types.

16. See part2-question16.js
    
17. The result would be [2,4,6]. We start with calling modifyArray, with the argument for callback being the doSomething function. The modifyArray function walks through each element of the list and then calls the function callback (in our case, doSomething. on each element and adds the returned element to a new list to return. Our doSomething function multiplies each argument by 2, so our returned list from modifyArray will multiply each element by 2 to get the new list.
    
18. See part2-question18.js
    
19. 1
    4
    3
    2