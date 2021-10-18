# DevTools Pt.2
1. The bug is that the values of num1 and num2 are objects/strings (meaning the type of result is a string of an object instead of a numerical value).
2. I would fix it by typecasting the values of num1 and num2 to a numerical value so that the addition performed is numerical addition and not string concatenation.