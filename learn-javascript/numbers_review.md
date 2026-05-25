# Numbers Review

Remember, in JavaScript all numbers are just "number" types. There is no distinction between "Float" types and "Integer" types.


```javascript
Addition
2 + 1;
// 3
```

```javascript
Subtraction
2 - 1;
// 1
```

```javascript
Multiplication
2 * 2;
// 4
```

```javascript
Division
3 / 2;
// 1.5 (still just a "number")
```


-----

In JavaScript, the design of the language is a bit different from languages like Python, C++, or Java when it comes to math.

In many other languages, there is a strict distinction between:

- Integers: Whole numbers like 5, -10, or 100.
- Floats: Numbers with decimal points like 5.5, 3.14, or -0.01.

However, the creators of JavaScript decided to keep things simple. Every number, whether it has a decimal point or not, is stored as the same underlying data type: a `Number`.

So, when you look at the value 5, JavaScript sees a number. When you look at 5.5, JavaScript also sees a number. There isn't a separate "Integer" or "Float" type in the language's type system to distinguish them; they both fall under that single umbrella.

This is why the answer is Number, Number. Both values are treated exactly the same by the engine!