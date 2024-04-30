1. The length of the `prices` array will be output to console since `i` is a `var` so it has function scope
2. "150" will be output to console since `discountedPrice` is a `var` so it has function scope
3. "150" will be output to console since `finalPrice` is a `var` so it has function scope
4. The function will return [50, 100, 150] since there are no errors
5. An error will occur because `i` is `let` so it only has block scope within the for loop
6. An error will occur because `discountedPrice` is `let` so it only has block scope within the for loop
7. "150" will be output to console since `finalPrice`'s scope is the function as that is where it is declared
8. The function will return [50, 100, 150] since there are no errors
9. An error will occur because `i` is `let` so it only has block scope within the for loop
10. An error will occur because `discountedPrice` is `const` which has the same scope as `let`, which is within the for loop only
11. The function will return [50, 100, 150] even though `discountedPrice` is a const because it is redeclared with each iteration of the for loop.
12. 
    A. student.name; \
    B. student['Grad Year']; \
    C. student.greeting(); \
    D. student['Favorite Teacher'][name]; \
    E. student.courseLoad[0]; \
13. \
    A. '32'  Since '3' is considered a string, `+` converts the 2 to a string and appends it \
    B. 1  Unlike the previous 1, `-` is not an operator on a string, so '3' is convered to a number \
    C. 3  `null` converts to 0 when converted \
    D. '3null'  Similar to A, `+` appends null to '3' \
    E. 4  true is not a string, but a boolean. It is converted to 1, and then added with 3 \
    F. 0  Similar to E, false is converted to 0, as is null, so the result is 0 \
    G. '3undefined'  Similar to D, undefined is appended to '3' \
    H. NaN  Similar to B, '3' is converted to 3, however undefined is convered to NaN (Not a Number) 
14. 
    A. true  '2' is converted to a number. 2 is greater than 1 \
    B. false  The two strings are compared character by character, and the first character of '12' is 1 \
    C. true  '2' is converted to a number, and 2 is equal to 2 \
    D. false  The `===` operator is a strict comparison, and doesn't convert '2' to a number \
    E. false  true is converted to a 1, and 1 does not equal 2 \
    F. true  Boolean(2) returns true, and true equals true \
15. `==` will convert different types occasionally resulting in truthy or falsy object comparisons. \
    `===` however is a strict comparison, and doesn't do any conversions, so similar but different types will still be false.
17. [2, 4, 6] In the for loop, each iteration will call the doSomething function using the function as a variable, passing the current array index and then pushing it onto the new array.
19. 1 4 3 2
