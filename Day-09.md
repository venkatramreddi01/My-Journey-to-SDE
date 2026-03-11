# Day 9 - Exception Handling & File I/O ✅

**Date:** February 27, 2026  
**Status:** COMPLETE  

## Topics Learned
- Exception handling (try-catch-finally)
- Throw and throws keywords
- Custom exceptions
- Checked vs unchecked exceptions
- File reading and writing
- File operations (create, delete, rename)
- BufferedReader/Writer
- Try-with-resources
- File-based applications

## Programs Written (10)
1. **ExceptionBasics** - Try-catch with division, arrays, parsing
2. **MultipleCatchBlocks** - Handling multiple exception types
3. **FinallyBlock** - Understanding finally execution
4. **ThrowExample** - Manual exception throwing
5. **CustomException** - Creating custom exception classes
6. **FileReadWrite** - Basic file read/write operations
7. **FileOperations** - File info, create, delete, rename, list
8. **StudentRecordSystem** - File-based student database
9. **LogFileManager** - Application logging system
10. **FileBackupSystem** - Complete backup and restore system

## Key Concepts

**Exception Handling:**
```java
try {
    // Code that might throw exception
} catch (ExceptionType e) {
    // Handle exception
} finally {
    // Always executes
}
```

**Throw vs Throws:**
```java
// throw - manually throw exception
throw new IllegalArgumentException("Error!");

// throws - declare method might throw
public void method() throws IOException { }
```

**Custom Exception:**
```java
class CustomException extends Exception {
    public CustomException(String message) {
        super(message);
    }
}
```

**File Operations:**
```java
// Read
Scanner scanner = new Scanner(new File("file.txt"));

// Write
FileWriter writer = new FileWriter("file.txt");
writer.write("content");

// Try-with-resources
try (FileWriter writer = new FileWriter("file.txt")) {
    // Automatically closed
}
```

## Challenges Overcome
- Understanding exception hierarchy
- Choosing checked vs unchecked exceptions
- Properly closing file resources
- Handling FileNotFoundException
- Creating meaningful custom exceptions
- Managing file paths and directories

## Key Takeaways
1. **Exceptions prevent crashes** - Handle errors gracefully
2. **Finally always executes** - Perfect for cleanup
3. **Try-with-resources is clean** - Auto-closes resources
4. **Custom exceptions add clarity** - Better error messages
5. **File I/O needs error handling** - Always use try-catch
6. **BufferedReader/Writer for performance** - Faster than basic streams

## Real-World Applications
- **Student Record System** - Persistent data storage
- **Log File Manager** - Application monitoring
- **File Backup System** - Data protection
- **Error handling** - Production-ready code

## Stats
- Day: 9/180 (5%)
- Programs: 10
- Total: 88 programs
- Hours: ~8

## Important Notes
**Exception Best Practices:**
- Catch specific exceptions first
- Don't catch Exception unless necessary
- Always clean up resources (use try-with-resources)
- Create custom exceptions for domain-specific errors
- Log exceptions for debugging

**File I/O Best Practices:**
- Always close streams
- Handle FileNotFoundException
- Use buffered streams for large files
- Check file existence before operations
- Use absolute paths when possible

## Tomorrow (Day 10)
Collections Framework - ArrayList, LinkedList, HashMap

---
**9 down, 171 to go! 🔥**
**Week 2: Day 3 complete! 💪**
