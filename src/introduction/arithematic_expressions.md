# Expressions

Expressions are elements that evaluate to a value. For example:

```javascript,readonly,norepl
10
1.2
-10
-1.2
```

A number is an expression that evaluates to itself. Here, 10 evaluates to 10, 1.2 evaluates to 1.2, and so on.

Similar to numbers, booleans and strings also evaluate to themselves.

```javascript,readonly,norepl
false // evaluate to false
true // evaluate to true
"Hello World!" // evaluate to "Hello World!"
```

These simple expressions can be combined to form complex expressions. For example, consider the expression below:

```javascript,readonly,norepl
10 + 23
```

This is a combined expression that performs the addition of two numbers. While evaluating the expression, the JavaScript runtime will evaluate 10. It then sees the addition operator (+) and knows it needs to evaluate the right-side expression and perform the addition of the left and right-side evaluated values. 23 will be evaluated, and then the addition of 10 and 23 will be evaluated to 33.

Let see a more complex expression.

```javascript,readonly,norepl
10 + 23 + 12
```

The evaluation of the expression will start from left to right.
Evaluation Steps:

- The expression 10 + 23 will evaluate to 33.
- We replace 10 + 23 with 33.
- We evaluate the new expression 33 + 12, which will be 45.

In this case, the expression consists only of addition (+). However, if the expression consists of different arithmetic operations, then the order of operations (operator precedence) determines the evaluation order.
