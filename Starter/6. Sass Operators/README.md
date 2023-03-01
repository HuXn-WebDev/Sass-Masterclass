# Operators?

### Operator is a symbol that tells the compiler to perform specific mathematical, conditional, or logical functions. It is a symbol that operates on a value or a variable.

# Equality Operator

### The equality operators return whether or not two values are the same

```scss
.selector {
  padding: 10px == 10px; // true
  padding: 10px == 10em; // false
  padding: 10px != 10px; // false
  padding: 10px != 10em; // true
}
```

# Relational Operator

### Relational operators are those which compare the values of two numbers. They tell whether one number is smaller or greater than or equal to the other number. They automatically convert numbers into compatible units.

```scss
.selector {
  margin: 100 > 50; // true
  margin: 10px < 17px; // true
  margin: 96px >= 1in; // true
  margin: 1000ms <= 1s; // true
}
```

# Boolean Operator

### A boolean refers to a value that is either true or false

- (and) If both conditions are true then the value will be true, otherwise FALSE.
- (or) If either conditions are true then the value will be true, otherwise FALSE.
- (not) Returns the opposite value.

```scss
.selector {
  ------------------------------------------------
  // both conditions are true so the answer will be true.
  margin: arial == "arial" and 10px == 10;
  // One condition is false so the answer will be false.
  margin: arial == "arial" and 10px == 20;
  ------------------------------------------------
  // One condition is true so the answer will be true.
  margin: arial == "arial" or 10px == 20;
  // Both conditions are false so the answer is false.
  margin: arial == "roboto" or 10px == 20;
  ------------------------------------------------

  ------------------------------------------------
  margin: not 10px == 10px; // false
  margin: not 10px == 20px; // true
  ------------------------------------------------
}
```
