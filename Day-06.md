# Day 6 - OOP: Classes & Objects ✅

**Date:** February 24, 2026  
**Status:** COMPLETE  

## Topics Learned
- Classes and Objects fundamentals
- Constructors (default and parameterized)
- Encapsulation (private fields, getters/setters)
- The `this` keyword
- Access modifiers (public, private)
- Static vs Instance variables/methods
- Object-oriented design principles

## Programs Written (10)
1. **PersonClass** - Basic class with fields and methods
2. **StudentWithConstructor** - Constructors and initialization
3. **BankAccount** - Encapsulation with deposit/withdraw
4. **Rectangle** - Calculation methods and validation
5. **Book** - Library management with availability tracking
6. **StaticExample** - Static variables and methods
7. **Employee** - Employee management with auto-generated IDs
8. **Circle** - Geometric calculations with constants
9. **Product** - E-commerce inventory management
10. **CarShowroom** - Comprehensive showroom system with menu

## Key Concepts

**Class Structure:**
```java
public class ClassName {
    // Fields (private for encapsulation)
    private String field1;
    private int field2;
    
    // Constructor
    public ClassName(String field1, int field2) {
        this.field1 = field1;
        this.field2 = field2;
    }
    
    // Getters
    public String getField1() { return field1; }
    
    // Setters
    public void setField1(String field1) { this.field1 = field1; }
    
    // Methods
    public void doSomething() { }
}
```

**Object Creation:**
```java
ClassName obj = new ClassName("value", 10);
obj.doSomething();
```

**Static vs Instance:**
```java
static int sharedVariable;    // Shared by all objects
int instanceVariable;         // Unique per object

static void staticMethod() { }   // Called via ClassName.method()
void instanceMethod() { }        // Called via object.method()
```

## Challenges Overcome
- Understanding class vs object relationship
- Using `this` keyword correctly in constructors
- Implementing proper encapsulation
- Differentiating static and instance members
- Managing object state and behavior
- Creating meaningful constructors

## Key Takeaways
1. **Class = Blueprint, Object = Instance** - Class defines structure, objects are actual entities
2. **Encapsulation is crucial** - Private fields + public getters/setters = data protection
3. **Constructors initialize objects** - Set up object state when created
4. **Static = shared, Instance = unique** - Static belongs to class, instance to objects
5. **this keyword** - Refers to current object, disambiguates fields from parameters
6. **Objects model real-world entities** - Cars, books, bank accounts, etc.

## Design Patterns Used
- Constructor overloading (default + parameterized)
- Getter/Setter pattern for encapsulation
- Validation in setters and methods
- Static counter for auto-generated IDs
- Status flags (boolean fields like `isAvailable`, `isSold`)

## Stats
- Day: 6/180 (3.33%)
- Programs: 10
- Total: 58 programs
- Hours: ~8

## Important Notes
**OOP Principles Applied:**
- Encapsulation: Data hiding with private fields
- Abstraction: Hiding complexity through methods
- Single Responsibility: Each class has one clear purpose

**Best Practices Learned:**
- Make fields private, methods public
- Use constructors for initialization
- Validate input in setters
- Use meaningful names for classes and methods
- Keep classes focused on single responsibility

## Tomorrow (Day 7)
OOP Advanced - Inheritance and Polymorphism

---
**6 down, 174 to go! 🔥**
