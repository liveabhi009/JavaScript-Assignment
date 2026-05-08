# 03-JavaScript Assignment – Variables

# Section A: Theory & Basics

## 1. What is a variable in JavaScript?

A variable in JavaScript is a container used to store data values.  
Variables help us save and use data in a program.

## 2. What is the difference between declaration, initialization, and re-assignment?

### Declaration

Creating a variable using `var`, `let`, or `const`.

```js
let age
```

### Initialization

Assigning a value to a variable.

```js
age = 20
```

### Re-assignment

Changing the value of a variable.

```js
age = 25
```

---

## 3. What are `let`, `var`, and `const`? What is the difference between them?

### `var`

* Can be redeclared
* Can be reassigned
* Function scoped

```js
var a = 10
var a = 20
a = 30
console.log(a)
```

### `let`

* Cannot be redeclared
* Can be reassigned
* Block scoped

```js
let a = 10
a = 20
console.log(a)
```

### `const`

* Cannot be redeclared
* Cannot be reassigned
* Block scoped

```js
const a = 10
console.log(a)
```

---

## 4. Create a greeting alert.

```js
let userName = prompt("Enter your name")
let message = `Good Morning ${userName}`
alert(message)
```

---

## 5. What are the naming conventions in JavaScript?

* Variable names should start with a letter, `_`, or `$`
* Do not use spaces in variable names
* Do not start variable names with numbers
* Use meaningful names
* Use camelCase naming style

### Example

```js
let firstName
let userAge
let totalAmount
```

---

# Section B: Practical Problems

## 6. Create variables for age, city, and isStudent. Print them in one sentence.

```js
let age = 22
let city = "Kochi"
let isStudent = true

console.log(`I am ${age} years old, I live in ${city}, and student status is ${isStudent}`)
```

---

## 7. Swap the values of two variables using a temp variable.

```js
let a =15
let b = 9
let temp = b

b=a
a=temp
console.log(a)
console.log(b);

```

---

## 8. Change a variable from number to string and print both values.

```js
let num = 100
console.log(num)
let str = num.toString()
console.log(str)
```

---

## 9. Combine firstName and lastName using template literals.

```js
let firstName = "John"
let lastName = "Doe"
let fullName = `${firstName} ${lastName}`
console.log(fullName)
```

---

## 10. Identify valid and invalid variable names.

### Valid Variable Names

```js
let userName
let _age
let $amount
let city123
```

### Invalid Variable Names

```js
let 123name
let my-name
let var
let user name
```