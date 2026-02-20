# Day 3 - Arrays Deep Dive ✅

**Date:** February 17-18, 2026  
**Status:** COMPLETE  

## 🎯 Topics Learned

**Core Concepts:**
- Array declaration and initialization
- Accessing array elements (indexing)
- Array length property
- Looping through arrays (for loop and enhanced for loop)
- 2D arrays (matrices)
- Common array operations

**Algorithms:**
- Linear search
- Bubble sort
- Finding max/min elements
- Array reversal
- Frequency counting
- Array rotation

## 💻 Programs Written (10)

### Basic Operations (4 programs)
1. **ArrayBasics.java** - Array declaration, initialization, and printing
2. **ArraySum.java** - Calculate sum of all array elements
3. **ArrayMax.java** - Find largest element in array
4. **ArrayReverse.java** - Reverse array in-place

### Search & Sort (2 programs)
5. **ArraySearch.java** - Linear search implementation
6. **ArraySort.java** - Bubble sort algorithm

### Advanced Operations (4 programs)
7. **ArraySecondLargest.java** - Find second largest element
8. **ArrayFrequency.java** - Count frequency of each element
9. **Matrix2D.java** - 2D array operations and sum
10. **ArrayRotation.java** - Rotate array by k positions

## 🔧 Key Concepts Mastered
```java
// Array declaration
int[] numbers = new int[5];
String[] names = {"Alice", "Bob", "Charlie"};

// Accessing elements
numbers[0] = 10;  // First element
numbers[numbers.length - 1] = 50;  // Last element

// Looping
for (int i = 0; i < arr.length; i++) {
    System.out.println(arr[i]);
}

// Enhanced for loop
for (int num : numbers) {
    System.out.println(num);
}

// 2D arrays
int[][] matrix = new int[3][3];
```

## 🚧 Challenges Faced

**Technical:**
- Understanding array indexing (0-based)
- Avoiding ArrayIndexOutOfBoundsException
- Implementing bubble sort logic
- Working with 2D array nested loops

**Tooling:**
- GitHub Desktop push issues
- Solved by uploading directly via GitHub website
- Learned alternative methods when primary tools fail

## ✅ Solutions & Learnings

- **Arrays are fixed size** - once created, size cannot change
- **Index starts at 0** - valid indices are 0 to length-1
- **Arrays.toString()** - proper way to print arrays
- **Nested loops** - essential for 2D arrays and certain algorithms
- **Swap technique** - using temp variable for element swapping

## 📊 Stats

- **Day:** 3/180 (1.67%)
- **Programs today:** 10
- **Total programs:** 28 (10 + 8 + 10)
- **Hours invested:** ~8 hours
- **GitHub commits:** 1
- **Lines of code:** ~250+

## 🎓 Key Takeaways

1. **Arrays are fundamental** - Foundation for data structures
2. **Algorithms matter** - Sorting and searching are everywhere
3. **Practice makes perfect** - Each program reinforced concepts
4. **Debugging skills** - Caught and fixed index errors
5. **Tool flexibility** - When GitHub Desktop fails, use website

## 🔄 Common Patterns Learned

**Finding Maximum:**
```java
int max = arr[0];
for (int i = 1; i < arr.length; i++) {
    if (arr[i] > max) max = arr[i];
}
```

**Reversing Array:**
```java
for (int i = 0; i < arr.length / 2; i++) {
    int temp = arr[i];
    arr[i] = arr[arr.length - 1 - i];
    arr[arr.length - 1 - i] = temp;
}
```

**Bubble Sort:**
```java
for (int i = 0; i < arr.length - 1; i++) {
    for (int j = 0; j < arr.length - 1 - i; j++) {
        if (arr[j] > arr[j + 1]) {
            // swap
        }
    }
}
```

## 🔗 Resources Used

- Programming with Mosh - Java Arrays Tutorial
- Java Documentation - Arrays class
- Practice problems - Self-created based on concepts

## 📝 Notes for Future

- Arrays are the foundation - master these first
- Will need these concepts for:
  - Data Structures (ArrayList, LinkedList)
  - Algorithm problems on LeetCode
  - Interview questions
- Sorting algorithms will be revisited in DSA
- 2D arrays essential for matrix problems

## 🎯 Tomorrow's Plan (Day 4)

**Topics:**
- Strings in Java
- String methods and operations
- String manipulation
- StringBuilder vs String

**Goal:** 10 string programs

---

**Progress:** 3 days down, 177 to go! 🔥  
**Momentum:** Building strong! 💪  
**Commitment:** Unwavering! 🚀
