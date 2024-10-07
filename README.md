# Data-Manipulation-with-JavaScript
// Math Problems

// The initial numbers that must be verified.
const n1 = 5;
const n2 = 15;
const n3 = 20;
const n4 = 10;

// Check one: add up to 50
// This is a fairly simple operation using
// arithmetic operators and a comparison.
const isSum50 = n1 + n2 + n3 + n4 == 50;

// Check two: at least two odd numbers
// Here, we use modulus to check if something is odd.
// Since % 2 is 0 if even and 1 if odd, we can use
// arithmetic to count the total number of odd numbers.
const isTwoOdd = (n1 % 2) + (n2 % 2) + (n3 % 2) + (n4 % 2) >= 2;

// Check three: no number larger than 25
// This time, we use the OR operator to check
// if ANY of the numbers is larger than 25.
const isOver25 = n1 > 25 || n2 > 25 || n3 > 25 || n4 > 25;

// Check four: all unique numbers
// This is long, and there are more efficient
// ways of handling it with other data structures
// that we will review later.
const isUnique =
  n1 != n2 && n1 != n3 && n1 != n4 && n2 != n3 && n2 != n4 && n3 != n4;

// Here, we put the results into a single variable
// for convenience. Note how we negate isOver25 using
// the ! operator. We could also have tested for
// "isUnder25" as an alternative.
const isValid = isSum50 && isTwoOdd && !isOver25 && isUnique;

// Finally, log the results.
console.log(isValid);


const areAllNumDivisibleBy5 = (num1 % 5 === 0) && (num2 % 5 === 0) && (num3 % 5 === 0) && (num4 % 5 === 0);
console.log(`Are all numbers divisible by 5: ${areAllNumDivisibleBy5}`);

const isNum1LargerNum4 = num1 > num4;
console.log(`Is the first number (${num1}) larger than the last number (${num4}): ${isFirstLargerThanLast}`);


const subtractionResult = num2 - num1;
console.log(`Subtraction result (num2 - num1): ${10}`);

const multiplicationResult = subtractionResult * num3;
console.log(`Multiplication result (subtraction result * num3): ${200}`);

const remainderResult = multiplicationResult % num4;
console.log(`Remainder of (multiplication result % num4): ${20}`);





const isUnderOrEqual25 = (num1 <= 25);
console.log(`Is the number (${5}) under or equal to 25: ${Under}`);


// Practical Math

const tripDistance = 1500 //miles;
const fuelEfficiency = { '55': 30, '60': 28, '75': 23 }; // miles per gallon
const fuelBudget = $175; 
const fuelCostPerGallon = $3; 

// Let's calculate gallons needed, cost, and trip duration










