# Day 5 - Methods & Recursion ✅

**Date:** February 20, 2026  
**Status:** COMPLETE  

## Topics Learned
- Methods: creation, parameters, return types
- Method overloading
- Variable scope
- Recursion: base case, recursive case
- Recursion vs Iteration

## Programs Written (10)
1. **MethodBasics** - Method fundamentals
2. **CalculatorMethods** - Operations using methods
3. **MethodOverloading** - Same name, different parameters
4. **PrimeChecker** - Prime checking with methods
5. **FactorialRecursion** - Factorial (recursive vs iterative)
6. **FibonacciRecursion** - Fibonacci sequence
7. **SumRecursion** - Sum numbers, digits, arrays
8. **PowerRecursion** - Calculate base^exp
9. **GCDRecursion** - Euclidean algorithm
10. **TowerOfHanoi** - Classic recursion puzzle

## Key Concepts

**Method Structure:**
```java
public static returnType methodName(parameters) {
    return value;
}
```

**Recursion Pattern:**
```java
public static int recursiveMethod(int n) {
    if (n <= 0) return 0;  // Base case
    return n + recursiveMethod(n - 1);  // Recursive case
}
```

**Common Recursive Algorithms:**
- Factorial: `if (n <= 1) return 1; return n * factorial(n - 1);`
- Fibonacci: `if (n <= 1) return n; return fib(n-1) + fib(n-2);`
- GCD: `if (b == 0) return a; return gcd(b, a % b);`

## Challenges Overcome
- Understanding recursion (method calling itself)
- Identifying base cases
- Preventing infinite recursion
- Tower of Hanoi logic
- Stack overflow errors

## Key Takeaways
1. Methods enable code reusability and organization
2. Recursion needs base case + progress toward it
3. Recursion = elegant but uses more memory
4. Use recursion for tree traversal, divide-and-conquer
5. Method overloading = same name, different parameters

## Stats
- Day: 5/180 (2.78%)
- Programs: 10
- Total: 48 programs
- Hours: ~7

## Tomorrow (Day 6)
Classes and Objects - OOP fundamentals

---
**5 down, 175 to go! 🔥**
