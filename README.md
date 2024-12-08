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
