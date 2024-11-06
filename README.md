int main() {
    int n, x;
    
    // Fibonacci part
    printf("Enter the number of terms for Fibonacci series: ");
    scanf("%d", &n);
    printFibonacci(n);
    
    // Prime number check part
    printf("Enter a number to check if it's prime: ");
    scanf("%d", &n);
    if (isPrime(n)) {
        printf("%d is a prime number.\n", n);
    } else {
        printf("%d is not a prime number.\n", n);
    }

    // x^x calculation part
    printf("Enter a number to calculate x^x: ");
    scanf("%d", &x);
    printf("%d^%d = %lld\n", x, x, powerOfXtoX(x));

    return 0;
}
