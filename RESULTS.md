-Using double(n) function in the console multiplied my number by two and the output was my original number times two.
2 Results
function double(n) { 
return n * 2 
}
double(5) output was 10
double(26) output was 52

-Using the multiply(n) function multiplied my chosen number by my input number and resulted in the multiplied result in the output.
function multiply(n) { 
return n * 3
} 
multiply(8) 
Output was 24

-Using the isOdd(n) function made the console output yes when i input 5 as my chosen number.
function isOdd(n) {
  return Math.abs(n % 2) === 1;
}
 console.log(isOdd(5));
 Output was true

 -Using the IsEven function did the same thing as the isOdd(function) but instead ouput me false for my chosen odd number.
 function isEven(n) {
  if (n % 2 === 0) {
    return true;
  } else {
    return false;
  }
}
console.log(isEven(9));
Output was false

-Using the square(n) function multiplied my chosen number by itself and outputed the result.
function square(n) {
  return n * n; // Multiplies n by itself
}
square(5);
Output was 10

