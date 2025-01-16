# 0x13. JavaScript - Objects, Scopes and Closures

## Project Description

The `0x13-javascript-objects-scopes-closures` project is designed to deepen your understanding of three core concepts in JavaScript: Objects, Scopes, and Closures. This project will help you develop a clear understanding of how JavaScript handles data, memory management, and function execution. These concepts are crucial for writing efficient and maintainable JavaScript code.

### Learning Objectives

By the end of this project, you will be familiar with:

1. **Objects:**
   - Understanding the fundamentals of objects in JavaScript.
   - Creating and modifying objects using different methods.
   - Accessing object properties and using them in real-world applications.

2. **Scopes:**
   - Understanding the concept of scope and the difference between global and local variables.
   - Recognizing how variable declarations with `var`, `let`, and `const` work in different scopes.
   - Understanding lexical scoping and how nested functions interact with the outer scope.

3. **Closures:**
   - Understanding closures and how inner functions can access variables from outer functions.
   - Recognizing how closures help manage data in asynchronous programming and event-driven applications.
   - Using closures effectively in JavaScript to create private data and encapsulate functionality.

## Project Requirements

- **JavaScript (ES6)** should be used for all code.
- You should be familiar with basic HTML and CSS, as the project may involve embedding JavaScript code in HTML files.
- This project does not require any third-party libraries, and it should focus on pure JavaScript code.

## Key Concepts

- **Objects:** JavaScript objects are collections of key-value pairs, and are used to represent real-world entities.
- **Scopes:** Scopes define the visibility of variables and functions. Understanding the difference between global and local scopes is critical for controlling variable accessibility.
- **Closures:** A closure occurs when a function retains access to variables from its outer (enclosing) function, even after that function has returned.

## Tasks

### Task 0: Basic Objects
- Create and manipulate objects using both the object literal and the `new Object()` syntax.
- Add properties and methods to objects.

### Task 1: Understanding Scopes
- Explore the differences between global and local scope.
- Create functions that demonstrate variable visibility and scoping.

### Task 2: Using Closures
- Implement closures to preserve function state and control access to variables.
- Use closures for data encapsulation and privacy.

## Example Usage

Here are examples of the types of tasks you may encounter in this project:

### Example 1: Working with Objects
```javascript
const car = {
    make: "Toyota",
    model: "Corolla",
    year: 2020,
    displayInfo: function() {
        console.log(`${this.year} ${this.make} ${this.model}`);
    }
};

car.displayInfo(); // Output: 2020 Toyota Corolla

