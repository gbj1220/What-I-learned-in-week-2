# What I learned in week 2

## *If Statements*

An if statement is a way to use true or false statements in order to execute commands. Use if to have a command execute when result is true. Then use else to have something else execute if the first statement isn't true. Ex...

function eXample(num) {
  if (num === 0) {
    return true;
  }
  else {
    return false;
  }
}


An if statement can be more than just true or false however. the else if function allows you to use as many arguments as you want to really specify what you are looking for. 


## *Booleans* 


***True or False ...***


Booleans can be used when you only have 2 options. They are very similar to the if statements. A boolean is always true or false. Booleans are often used in if else statements and other loops. It's just a way to check multiple things using true and false. Ex... 


## *Functions in parameters*


We did a lot of work with basic functions using new parameters. We got to do some research and learn how to use different math operators to make our conditions true. We also learned how to find if a number is even or odd, between 2 values, and solve for other situations. Ex... 


function fizzy(num) {
  if (num % 15 === 0) {
    return 'FizzBuzz';
  } 
  
  if (num % 3 === 0 && num % 5 !== 0) {
    return 'Fizz';
  }
  
  if (num % 3 !== 0 && num % 5 === 0) {
    return 'Buzz';
  }
  
  if (num % 3 !== 0 && num % 5 !== 0) {
    return num
  }
}

