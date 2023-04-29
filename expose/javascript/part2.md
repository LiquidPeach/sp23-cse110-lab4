1. `i`s final value, `3`, will be outputted to the consol because it was declared as a `var` in the `for` loop.
   
2. `discountedPrice` will be outputted to the console because it was declared as a `var` and is allowed to be accessed outside of the code block it was declared in.
   
3. `finalPrice` will be outputted to the console because it was declared as a `var` and is allowed to be accessed outside of the code block it was declared in. The value of `finalPrice` was also changed in the `for` loop since it is able to be accessed inside of the loops code block.
   
4. It will return an array of discounted prices because `discount`, the return value of the function, is an array that contains the modified values of the `prices`, a parameter of the function.
   
5. This is an error because the `i` is a `let` variable, which can only be accessed within the function it was declared in. Since line 12 is trying to access it outside of the `for` loops code block, an error occurs.
   
6. This is an error because `discountedPrice` was declared as a `let` variable and cannot be accessed outside of the code block it was declared in. Line 13 is attempting to access it outside of the `for` loop, so an error occurs.
   
7. This returns the final value of `finalPrice`, which will be the value of the last computed `discountedPrice` in the loop. Line 14 is able to access it because it was declared in the same code block as line 14.
   
8. The function will return the array of the modified prices that were passed down to it as input. The return variable `discounted` was declared within the scope of the return statement, so it will return its value and safely delete `discounted` from memory.
   
9.  This is an error because the `i` is a `let` variable, which can only be accessed within the function it was declared in. Since line 11 is trying to access it outside of the `for` loops code block, an error occurs.
    
10. This outputs the value of `length` because line 12 is accessing it from within its scope.
    
11. The function will return the array of the modified prices that were passed down to it as input. Declaring the `discounted` array as `const` does not prevent pushing to the array or modifying the arrays elements. You simply cannot reassign the declared variables value.
    
12. (a) student.name<br>
    (b) student["Grad Year"]<br>
    (c) student.greeting()<br>
    (d) student['Favorite Teacher'].name<br>
    (e) student.courseLoad[0]<br>

13. (a) `'32'` because the `+` is used to concatenate strings, and because `2` is mapped to its exact string representation, the output will be a string that concatenates `'3'` and `'2'`.<br>
    (b) `1` because the operator `-` cannot subtract strings, so `'3'` is mapped to its integer form and the operation conputes `1`.<br>
    (c) `3` because `null` converts to `0`. `3 + 0 = 0`.<br>
    (d) `'3null'` because `null` is converted to its string form and is concatenated with `'3'`.<br>
    (e) `4` because `true` maps to `1`.<br>
    (f) `0` because both `false` and `null` convert to 0.<br>
    (g) `'3undefined'` because `undefined` is converted to its string form and is concatenated with `'3'`.<br>
    (h) `NaN` because after `'3'` is converted to an integer, the interpreter is attempting to do subtraction on a variable that does not have a value.

14. (a) `true` because `'2'` becomes the integer `2`, which is bigger than `1`.<br>
    (b) `false` because the first character in `'12'` is smaller than the first character in `'2'`.<br>
    (c) `true` because an equality check using `==` converts the values types before comparing, so `'2'` becomes `2`.<br>
    (d) `false` because `===` does not convert the values types. If both values are not of the same type, there will be no attempt in comparing them and `false` is returned.<br>
    (e) `false` because `true` maps to `1`, which is not equal to `2`.<br>
    (f) `true` because the `Boolean()` function considers the boolean value of `2` as `true`.

15. `==` will compare values even if they are different types. It will convert the type of a value and then check for equality. `===` will not check for equality if the two values are not of the same type, it will return `false` and not attempt to convert anything.

17. `modifyArray` returns the array `[2, 4, 6]`. First it declares tje const array `newArray` which will hold the modified values of the input `array`. The `for` loop iterates through `array` and when `newArray` calls `push`, it uses `callback(array[i])` as a parameter. `callback` is the function `doSomething`, which takes a number as a parameter, in our case `array[i]`, and multiplies it by 2. After `doSomething` returns the modified number, it is pushed into `newArr`. Once the `for` loop is finished, it returns the new array.

19. 1 4 3 2