# Basic-programming
function isPrime(num) {
    if (num <= 1) return false; // Numbers less than or equal to 1 are not prime
    for (let i = 2; i <= Math.sqrt(num); i++) {
        if (num % i === 0) return false; // Divisible by a number other than 1 and itself
    }
    return true; // Prime number
}

console.log(isPrime(5)); // Example test: true
console.log(isPrime(4)); // Example test: false




function isEven(num) {
    return num % 2 === 0; // Returns true if even, false if odd
}

console.log(isEven(4)); // Example test: true
console.log(isEven(5)); // Example test: false
