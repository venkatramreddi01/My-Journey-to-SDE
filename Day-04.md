# Day 4 - Strings ✅

**Date:** February 19, 2026  
**Status:** COMPLETE  

## Topics Learned
- String methods and manipulation
- String vs StringBuilder (immutability)
- String comparison (equals vs ==)
- Character arrays and conversion
- String algorithms

## Programs Written (10)
1. **StringBasics** - String creation, methods, comparison
2. **StringReverse** - Reverse string (3 methods)
3. **PalindromeChecker** - Check if string reads same both ways
4. **VowelCounter** - Count vowels and consonants
5. **WordCounter** - Count and display words
6. **StringCaseConverter** - Upper, lower, toggle, title case
7. **AnagramChecker** - Check if two strings are anagrams
8. **StringCompressor** - Compress consecutive chars ("aaabbc" → "a3b2c1")
9. **StringPermutations** - Generate all permutations (recursion)
10. **LongestWord** - Find longest word in sentence

## Key Concepts

**String Immutability:**
```java
String s = "Hello";
s.concat(" World");  // Creates new object
// Use StringBuilder for modifications
```

**Important Methods:**
- `length()`, `charAt()`, `substring()`
- `equals()`, `equalsIgnoreCase()` 
- `toUpperCase()`, `toLowerCase()`, `trim()`
- `split()`, `replace()`, `contains()`

**Common Patterns:**
```java
// Reverse
String reversed = new StringBuilder(str).reverse().toString();

// Palindrome
boolean isPalindrome = str.equals(new StringBuilder(str).reverse().toString());

// Count chars
for (char c : str.toCharArray()) { }
```

## Challenges Overcome
- Understanding immutability and String pool
- String concatenation in loops (inefficient)
- Using `.equals()` instead of `==`
- Recursive permutation logic
- Handling edge cases (empty strings, spaces)

## Key Takeaways
1. Always use `.equals()` for string comparison
2. Use StringBuilder for multiple modifications
3. Strings are immutable - creates new objects
4. Character arrays useful for manipulation
5. Many interview problems involve strings

## Stats
- Day: 4/180 (2.22%)
- Programs: 10
- Total: 38 programs
- Hours: ~7

## Tomorrow (Day 5)
Methods, function overloading, recursion deep dive

---
**4 down, 176 to go! 🔥**
