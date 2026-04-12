# Day 12 - Collections Framework Part 3 ✅

**Date:** March 2, 2026  
**Status:** COMPLETE  

## Topics Learned
- Stack (LIFO - Last In First Out)
- Queue (FIFO - First In First Out)
- Deque (Double-Ended Queue)
- PriorityQueue (Heap-based)
- ArrayDeque (Best implementation)
- Stack vs Queue vs Deque comparison

## Programs Written (10)
1. **StackBasics** - push, pop, peek, search operations
2. **BrowserHistory** - Back/Forward navigation simulator
3. **BalancedParentheses** - Bracket matching validator
4. **QueueBasics** - offer, poll, peek operations
5. **PrinterQueue** - Print job management system
6. **DequeBasics** - Both-end operations, Stack/Queue modes
7. **PriorityQueueBasics** - Min/Max heap operations
8. **TaskScheduler** - Priority-based task execution
9. **UndoRedoSystem** - Text editor with undo/redo
10. **CollectionPerformance** - Performance comparison

## Key Concepts

**Stack (LIFO):**
```java
Stack<Integer> stack = new Stack<>();
stack.push(10);      // Add to top
int top = stack.pop();     // Remove from top
int peek = stack.peek();   // View top
```

**Queue (FIFO):**
```java
Queue<String> queue = new LinkedList<>();
queue.offer("item");     // Add to end
String front = queue.poll();   // Remove from front
String peek = queue.peek();    // View front
```

**Deque (Both Ends):**
```java
Deque<Integer> deque = new ArrayDeque<>();
deque.addFirst(1);    // Add to start
deque.addLast(2);     // Add to end
deque.removeFirst();  // Remove from start
deque.removeLast();   // Remove from end
```

**PriorityQueue (Heap):**
```java
PriorityQueue<Integer> pq = new PriorityQueue<>();
pq.offer(30);
pq.offer(10);
pq.poll();  // Returns 10 (smallest first)
```

## Comparison Table

| Feature | Stack | Queue | Deque | PriorityQueue |
|---------|-------|-------|-------|---------------|
| **Order** | LIFO | FIFO | Both ends | Priority-based |
| **Insert** | O(1) | O(1) | O(1) | O(log n) |
| **Remove** | O(1) | O(1) | O(1) | O(log n) |
| **Peek** | O(1) | O(1) | O(1) | O(1) |

## Use Cases

**Stack:**
- Undo/Redo functionality
- Browser back button
- Expression evaluation
- Balanced parentheses checking
- Function call stack

**Queue:**
- Task scheduling
- Print job management
- BFS algorithm
- Request handling
- Message queuing

**Deque:**
- Browser history (forward/back)
- Sliding window problems
- Can replace both Stack and Queue
- Work-stealing algorithms

**PriorityQueue:**
- Task scheduling by priority
- Dijkstra's algorithm
- Event simulation
- Top K problems
- Huffman coding

## Key Takeaways
1. **Use ArrayDeque over Stack class** - Faster, not synchronized
2. **ArrayDeque for both Stack and Queue** - Best performance
3. **PriorityQueue for heap operations** - Auto-sorts by priority
4. **poll()/peek() safer than remove()/element()** - Returns null vs exception
5. **Deque most versatile** - Can work as Stack or Queue

## Stats
- Programs: 10 (Total: 118)
- Day: 12/180 (6.67%)
- Week 2: 5/7 complete

## Collections Framework Complete! 🎉
Days 10-12 covered all major collections:
- ✅ ArrayList, LinkedList, Vector
- ✅ HashMap, HashSet, TreeMap, TreeSet
- ✅ Stack, Queue, Deque, PriorityQueue

## Tomorrow (Day 13)
Comparator & Comparable - Custom Sorting

---
**12 down, 168 to go! 🔥**
**Collections Framework MASTERED! 💪**
