# JavaScript Data Types Assignment

## Section A: Basic Questions

1. **What are data types in JavaScript?**  
   Data types specify the type of data that a variable can hold, such as numbers, strings, booleans, etc. They determine what operations can be performed on the data.

2. **List all primitive data types in JavaScript.**  
   - Number  
   - String  
   - Boolean  
   - Undefined  
   - Null  
   - Symbol  
   - BigInt

3. **What is the difference between primitive and non-primitive data types?**  
   - *Primitive data types* hold simple, single values and are immutable.  
   - *Non-primitive data types* (objects, arrays, functions) can hold collections of data or complex structures and are mutable.

4. **What is the `typeof` operator? Give examples.**  
   The `typeof` operator returns a string indicating the data type of a value.  
   ```
   javascript
   console.log(typeof 42); 
   console.log(typeof "hello"); 
   console.log(typeof true);
    
   ```

5. **What is the `undefined` data type?**  
   It indicates a variable has been declared but not assigned a value.

6. **What is `null` in JavaScript?**  
   `null` is an assigned value that represents 'no value' or 'nothing'.

7. **What is the difference between `null` and `undefined`?**  
   - `undefined` means a variable has been declared but not assigned a value.  
   - `null` is an explicit assignment indicating 'no value'.

8. **What is the `boolean` data type? Give examples.**  
   It represents logical values: `true` or `false`.  
   ```
   javascript
   let isJavaScriptFun = true;
   let isSkyGreen = false;

   ```

9. **What is a `string` in JavaScript?**  
   A sequence of characters enclosed in quotes, e.g., `"Hello"` or `'World'`.

10. **What is a `number` data type? Does JavaScript support integers and floats separately?**  
    JavaScript uses the `Number` type for both integers and floating-point numbers. It does not differentiate between integer and float at the type level.

---

## Section B: Conceptual Questions

11. **What is the `symbol` data type in JavaScript?**  
    A `symbol` is a unique, immutable primitive value often used as identifiers for object properties.

12. **What is `bigint` and why is it used?**  
    `BigInt` is a primitive type for representing integers larger than `Number.MAX_SAFE_INTEGER`. It is used when handling large integers.

13. **What happens when you use `typeof null`?**  
    It returns `"object"`, which is considered a historical bug in JavaScript.

14. **Explain type coercion with examples.**  
    JavaScript automatically converts values from one type to another in certain operations.  
    Example: `'5' + 10` results in `'510'` (string), while `'5' - 10` results in `-5` (number).

15. **What is implicit and explicit type conversion?**  
    - *Implicit conversion* happens automatically (e.g., `5 + '5'`).  
    - *Explicit conversion* requires manual methods like `Number()`, `String()`.

16. **What is `NaN`? When does it occur?**  
    `NaN` stands for "Not-a-Number" and occurs when a mathematical operation fails, e.g., `0/0`.

---

## Section C: Practical / Coding Questions

17. **Write a program to check the data type of a variable.**  
    ```
    javascript
    let myVar = 42;
    console.log(typeof myVar);

    ```

18. **Declare variables of all primitive data types and print their types.**  
    ```
    javascript
    let num = 100;
    let str = "Hello";
    let bool = true;
    let undef;
    let nul = null;
    let sym = Symbol('sym');
    let big = BigInt(9007199254740991);
    
    console.log(typeof num);   
    console.log(typeof str);    
    console.log(typeof bool);  
    console.log(typeof undef);  
    console.log(typeof nul);   
    console.log(typeof sym);   
    console.log(typeof big); 

    ```

19. **Write a program to convert a string to a number.**  
    ```
    javascript
    let str = "123";
    let num = Number(str);
    console.log(num);

    ```

20. **Write a program to convert a number to a string.**  
    ```
    javascript
    let num = 456;
    let str = num.toString();
    console.log(str); 

    ```

21. **What will be the output of:**
    ```
    javascript
    console.log(typeof 42);         
    console.log(typeof "Hello");    
    console.log(typeof true);       
    console.log(typeof undefined);  
    console.log(typeof null); 

    ```

22. **Predict the output:**
    ```
    javascript
    console.log(5 + "5");
    console.log("5" - 2);      
    console.log(true + 1);    
    console.log(false + "hello");

    ```

23. **Create an object and an array, then check their data types using `typeof`.**  
    ```
    javascript
    const obj = { name: "John" };
    const arr = [1, 2, 3];
    console.log(typeof obj); 
    console.log(typeof arr); 

    ```

---

## Section D: Advanced Thinking

24. **Can a variable change its data type? Explain with example.**  
    Yes, JavaScript is dynamically typed. You can assign different types to the same variable.  
    ```
    javascript
    let data = 10; // number
    data = "Now I'm a string"; // string

    ```

25. **How does JavaScript handle large integers?**  
    JavaScript uses `Number` which can safely represent integers up to `Number.MAX_SAFE_INTEGER` (2^53 - 1). For larger integers, `BigInt` is used.

---
