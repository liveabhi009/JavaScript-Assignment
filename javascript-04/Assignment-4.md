
# JavaScript Operators and Programs

## Section A – Basic Questions

### 1. What are operators in JavaScript?
Operators in JavaScript are special symbols or keywords used to perform operations on variables and values. They allow us to manipulate data, perform calculations, compare values, and combine expressions.

### 2. What is the difference between arithmetic operators and assignment operators?
- **Arithmetic Operators** perform mathematical operations.  
  Eg: `+`, `-`, `*`, `/`, `%`

- **Assignment Operators** assign values to variables.  
  Eg: `=`, `+=`, `-=`, `*=`, `/=`

### 3. Explain the purpose of comparison operators with Egs.
Comparison operators compare two values and return `true` or `false`.

Egs:
```js
5 == "5" 
5 === "5"  
10 > 5     
3 < 7    
````

### 4. What is the difference between `==` and `===` in JavaScript?

* `==` checks value equality after type conversion.
* `===` checks both value and data type.

Eg:

```js
"5" == 5  
"5" === 5  
```

### 5. What is the difference between `!=` and `!==`?

* `!=` checks inequality after type conversion.
* `!==` checks strict inequality without type conversion.

Eg:

```js
"5" != 5   
"5" !== 5  
```

### 6. What are logical operators? Explain `&&`, `||`, and `!`.

Logical operators are used with boolean values.

* `&&` → AND
* `||` → OR
* `!` → NOT

Egs:

```js
true && false 
true || false 
!true         
```

### 7. What is the purpose of the modulus (`%`) operator?

The modulus operator returns the remainder after division.

Eg:

```js
10 % 3 // 1
```

### 8. What is the increment operator?

The increment operator (`++`) increases a value by 1.

* Pre-increment: `++x`
* Post-increment: `x++`

### 9. What is the decrement operator?

The decrement operator (`--`) decreases a value by 1.

Eg:

```js
x--
--x
```

### 10. What is operator precedence in JavaScript?

Operator precedence decides which operation is performed first in an expression.

Eg:

```js
2 + 3 * 4 
```

---

# Section B – Output Prediction

### 11. Predict the output:

```js
let a = 10;
let b = 3;

console.log(a + b); 
console.log(a - b); 
console.log(a * b); 
console.log(a / b); 
console.log(a % b); 
```

### 12. Predict the output:

```js
let x = 5;

console.log(x++); 
console.log(x);  
```

### 13. Predict the output:

```js
let x = 5;

console.log(++x); 
console.log(x);   
```

### 14. Predict the output:

```js
console.log(10 == "10");  
console.log(10 === "10"); 
```

### 15. Predict the output:

```js
console.log(true && false); 
console.log(true || false); 
console.log(!true);        
```

### 16. Predict the output:

```js
let a = 8;

a += 2;
a *= 3;

console.log(a); 
```

### 17. Predict the output:

```js
console.log(5 > 3 && 10 < 20); 
console.log(5 > 10 || 8 == 8); 
```

### 18. Predict the output:

```js
console.log(10 + "5"); 
console.log("10" - 5); 
```

---

# Section C – Write Programs

### 19. Add Two Numbers

```js
let num1 = 5;
let num2 = 10;

let sum = num1 + num2;

console.log("Sum:", sum);
```

### 20. Calculate Area of Rectangle

```js
let length = 10;
let breadth = 5;

let area = length * breadth;

console.log("Area:", area);
```

### 21. Swap Two Numbers Using Third Variable

```js
let a = 5;
let b = 10;

let temp = a;
a = b;
b = temp;

console.log(a, b);
```

### 22. Swap Two Numbers Without Third Variable

```js
let a = 5;
let b = 10;

a = a + b;
b = a - b;
a = a - b;

console.log(a, b);
```

### 23. Calculate Annual Interest

```js
let P = 1000;
let R = 5;
let T = 2;

let I = (P * R * T) / 100;

console.log("Interest:", I);
```

### 24. Convert Fahrenheit to Celsius

```js
let F = 100;

let C = ((F - 32) * 5) / 9;

console.log("Celsius:", C);
```

### 25. BMI Calculator

```js
let weight = 70;
let height = 1.75;

let BMI = weight / (height * height);

console.log("BMI:", BMI);
```

### 26. Discount Percentage Calculator

```js
let MRP = 500;
let sellingPrice = 400;

let discount = ((MRP - sellingPrice) * 100) / MRP;

console.log("Discount:", discount);
```

---

# Section D – Advanced / Conceptual Questions

### 27. Explain type coercion in JavaScript with Egs.

Type coercion means automatic conversion from one data type to another.

Eg:

```js
"5" + 2 
"5" - 2 
```

### 28. Why does `"5" + 2` produce a different result from `"5" - 2`?

* `+` performs string concatenation.
* `-` converts strings to numbers.

Eg:

```js
"5" + 2 
"5" - 2 
```

### 29. What is short-circuit evaluation in logical operators?

Short-circuit evaluation stops checking once the result is known.

Eg:

```js
false && true 
true || false 
```

### 30. Predict the output:

```js
console.log(true + true);
console.log(false + 1);   

### 31. Explain truthy and falsy values in JavaScript.

### Truthy Values

Values treated as `true`.

Egs:

```js
"hello"
1
[]
{}
```

### Falsy Values

Values treated as `false`.

Eg:

```js
false
0
""
null
undefined
NaN
```

---
