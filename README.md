# Codewars-8KYU
#In this Repo, i will show how I solved a Kata in Codewars Challenge and show you 11 ways of converting a string in JavaScript to a number


**Description of the challenge**
We need a function that can transform a string into a number. What ways of achieving this do you know?

Note: Don't worry, all inputs will be strings, and every string is a perfectly valid representation of an integral number.

#Examples#
``"1234" --> 1234``
``"605"  --> 605``
``"1405" --> 1405``
``"-7" --> -7``

# The 11 Ways of Converting strings to number in JavaScript
1. Using the Number() Function
```
function stringToNumber(str) {
    return Number(str);
 }
```

2. using the parseInt() function
```
    const stringToNumber = function(str){
        return parseInt(str);
    }
```
3. using the parseFloat() function
```
    const stringToNumber = function(str){
        return parseFloat(str);
    }
```
4. using the unary plus operator (+)
```
    const stringToNumber = function(str){
        return (+str);
    }
```
5. multiplying the string by the number 1
```
    const stringToNumber = function(str){
        return (str * 1 );
    }
```
6. dividing the string by the number 1
```
    const stringToNumber = function(str){
        return (str / 1 );
    }
```
7. subtracting the number 0 from the string
```
    const stringToNumber = function(str){
        return (str - 0);
    }
```
8. using the bitwise NOT operator (~)
```
    const stringToNumber = function(str){
        return (~str);
    }
```
9. using the Math.floor() function
```
    const stringToNumber = function(str){
        return Math.Floor(str);
    }
```
10. using the Math.ceil() function
```
    const stringToNumber = function(str){
        return Math.ceil(str);
    }
```
11. using the Math.round() function
```
    const stringToNumber = function(str){
        return Math.round(str);
    }
```

