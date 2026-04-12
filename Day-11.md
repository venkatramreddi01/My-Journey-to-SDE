# Day 11 - Collections Framework Part 2 ✅

**Date:** March 1, 2026  
**Status:** COMPLETE  

## Topics Learned
- HashMap (key-value pairs)
- LinkedHashMap (insertion order)
- TreeMap (sorted keys)
- HashSet (unique elements)
- LinkedHashSet (unique + order)
- TreeSet (unique + sorted)
- Map and Set operations

## Programs Written (10)
1. **HashMapBasics** - put, get, containsKey, iteration methods
2. **StudentGrades** - Grade management with statistics
3. **WordFrequency** - Count word occurrences in text
4. **PhoneBook** - Contact directory with HashMap
5. **HashSetBasics** - Unique elements, set operations
6. **LinkedHashMapExample** - Insertion order maintenance
7. **TreeMapExample** - Sorted keys, navigation methods
8. **TreeSetExample** - Sorted unique elements
9. **CountryCapitals** - Country-capital mapping with quiz
10. **CollectionComparison** - Performance and use-case comparison

## Key Concepts

**HashMap:**
```java
HashMap<String, Integer> map = new HashMap<>();
map.put("key", 100);
int value = map.get("key");
map.containsKey("key");
map.forEach((k, v) -> System.out.println(k + "=" + v));
```

**HashSet:**
```java
HashSet<String> set = new HashSet<>();
set.add("item");
set.add("item");  // Duplicate ignored
boolean has = set.contains("item");
```

## Map Comparison

| Feature | HashMap | LinkedHashMap | TreeMap |
|---------|---------|---------------|---------|
| **Order** | No order | Insertion order | Sorted by key |
| **Performance** | O(1) | O(1) | O(log n) |
| **Null Keys** | 1 allowed | 1 allowed | Not allowed |
| **Use When** | Default choice | Order matters | Sorted keys needed |

## Set Comparison

| Feature | HashSet | LinkedHashSet | TreeSet |
|---------|---------|---------------|---------|
| **Order** | No order | Insertion order | Sorted |
| **Performance** | O(1) | O(1) | O(log n) |
| **Use When** | Uniqueness only | Unique + order | Unique + sorted |

## When to Use What?

**HashMap** - Default choice, fastest, no order needed  
**LinkedHashMap** - Cache systems, history, order matters  
**TreeMap** - Sorted keys, range queries, first/last operations

**HashSet** - Unique elements, fastest lookups  
**LinkedHashSet** - Unique + maintain order  
**TreeSet** - Unique + sorted, navigation operations

## Key Takeaways
1. **HashMap is king** - Most commonly used map
2. **HashSet for uniqueness** - Automatic duplicate removal
3. **Tree* for sorting** - TreeMap/TreeSet auto-sort
4. **Linked* for order** - Maintains insertion sequence
5. **Map iteration** - Use entrySet() for efficiency
6. **Set operations** - Union, intersection, difference

## Stats
- Programs: 10 (Total: 108)
- Day: 11/180 (6.11%)
- Week 2: 4/7 complete

## Tomorrow (Day 12)
Collections Part 3 - Stack, Queue, Deque, PriorityQueue

---
**11 down, 169 to go! 🔥**
