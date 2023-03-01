# Sass Functions

### Functions allow you to define complex operations on SassScript values that you can re-use throughout your stylesheet.

### They make it easy to abstract out common formulas and behaviors in a readable way.

```scss
@function pow($base, $exponent) {
  $result: 1;
  @for $_ from 1 through $exponent {
    $result: $result * $base;
  }
  @return $result;
}

.sidebar {
  float: left;
  margin-left: pow(4, 3) * 1px;
}
```

# Built-in Functions?

### Learn About Built-in Functions here 👇

```scss
// 👉  https://www.koderhq.com/tutorial/sass/native-functions/
```
