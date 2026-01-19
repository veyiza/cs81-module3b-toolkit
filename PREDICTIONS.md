The function double(n) will multiply any numbert by 2 and should produce my result.
2 double(n) function tests
double(5) 
double(26)
n * 2

The function multiply(n) will work very similar to the double(n) function and will multiply my desired number by my input number.
1 multiply(n) test
multiply(8) 
n * 3

The isOdd(n) function will make the console tell me if my chosen number is odd.
1 isOdd(n) function
function isOdd(n) {
  return Math.abs(n % 2) === 1;
}
 console.log(isOdd(5));

 
The isEven(n) function will tell me if my chosen number is Even or not. (Opposite of isOdd(n))
1 isEven(n) function
function isEven(n) {
  if (n % 2 === 0) {
    return true;
  } else {
    return false;
  }
}

The square(n) function should multiply my chosen number by itself and give me the result in the output.
1 square(n) function 
function square(n) { 
return n * n 
{
  square(6) 
