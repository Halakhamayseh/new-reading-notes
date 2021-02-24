# comparison operators 
1. Evaluating conditions :
you can evluate a situation by comparing one value in the script to what you expect it might be .
1. Less than or equal to (<=)it is returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
Greater than or equal to (>=)it is  returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
Equal to (===) it is returns true if the value on the left is equal to the value on the right, otherwise it returns false.
Not equal to (!==) i is returns true if the value on the left is not equal to the value on the right, otherwise it returns false.
 # logical operators
 comparison operators usually return a single value of true and false., we can use logical operators to make these assertions.
&& (and) This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
|| (or) This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
# loops
1. While loop
The while loop loops through a block of code as long as a specified condition is true.
EX var text = "";
var i = 0;
while (i < 5) {
  text += "<br>The number is " + i;
  i++;
}
For loop
The for loop has the following syntax:
for (statement 1; statement 2; statement 3) {
   code block to be executed
}
