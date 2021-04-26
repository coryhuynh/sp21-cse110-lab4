# Part 1. Intro to Javascript
## Part 1a. Quick Introduction
1. line 9 prints 'values added: ' followed by the sum of num1 and num2 if the variable add is true. In this case since the functino call is sumVlaues(10,10 true) line 19 will return 'values added: 20'.
2. line 13 will return the 'final result: 20'.
3. line 9 will return 'values added: 20'
4. line 13 will return an error because the variable result is outside of line 13's scope
5. line 9 will return an error because a const variable can not be reassigned which happens on line 7.
6. line 13 will return an error because the result variable is out of line 13's scope

## Part 1b. A Little More of a Challenge...
1. line 12 will print out '3' because that is the value of the variable i in the for loop starting on line 6 after the for loop ends (ends when i = prices.length) which is assigned as 'var' so there is no block scope.
2. line 13 will print out '150' which is the value of the variable discountedPrice during the last iteration of the for loop. This is because it is assigned as 'var' so there is no block scope.
3. line 14 will print out '150' which is the value of the variable finalPrice during the last iteration of the for loop. 
4. This function will return an array of all the prices in the input array 'prices' discounted by a percentage given by the input variable 'discount'
5. This cause an error because the variable i in the for loop is declared with 'let' and it is referred to in line 12 which is out of scope.
6. This also causes an error because the variable discountedPrice uses the word 'let' in its declaration and line 13 is out of its scope
7. line 14 will print out '150' which is the value of the variable finalPrice during the last iteration of the for loop. This works because while finalPrice uses the 'let' keyword in its declaration it is in the same scope as line 14.
8. This function will return an array of all the prices in the input array 'prices' discounted by a percentage given by the input variable 'discount'
9. line 11 will causes an error because the variable i in the for loop is declared with 'let' and it is referred to in line 11 which is out of scope.
10. Line 12 prints out '3' which is the value of the const variable 'length' which is assigned to the length of the prices array which is 3
11. This function will return an array of all the prices in the input array 'prices' discounted by a percentage given by the input variable 'discount'. It works because while 'discounted' is declared as const it is not being reassigned, only modified.
12. A. student[]().name;  
    B. student["Grad Year"];  
    C. student.greeting();  
    D. student["Favorite Teacher"].name;  
    E. student.courseLoad[0];
13. A. '32', 2 maps to string representation  
    B. 1, '3' maps to integer 3  
    C. 3, null maps to integer 0  
    D. '3null', null maps to string representation 'null'  
    E. 4, true maps to integer 1  
    F. 0, false maps to integer 0 and null maps to integer 0  
    G. '3undefined', undefined maps to string representation 'undefined'  
    H. NaN, undefined maps to NaN
14. A. true, '2' maps to integer 2  
    B. false, compares first characters of strings first  
    C. true, non-strict comparison '2' becomes integer 2  
    D. false, strict comparison  
    E. false, true becomes 1  
    F. true, Boolean(2) becomes true  
15. === is the strict equality check which also checks different types, == is non-strict and compares after conversion of different types
16. [part1b-question16.js](part1b-question16.js)
17. The result of the function call will return an array of numbers: [2,4,6]. The function doSomething takes a number and multiples it by 2. This function is passed in as a parameter to modifyArray. The function modifyArray goes through all numbers in the array [1,2,3] creates a new array with these numbers multiplied by 2 by using the callback function doSomething.
18. [part1b-question18.js](part1b-question18.js)
19. The code prints '1' and '4' then '3' then after 1 second '2'.




    