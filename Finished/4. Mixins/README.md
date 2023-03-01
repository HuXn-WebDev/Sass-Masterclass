# Sass Mixins

### The @mixin directive lets you create CSS code that is to be reused throughout the website.

### The @include directive is created to let you use (include) the mixin.

# Defining a Mixin

```scss
@mixin important-text {
  color: red;
  font-size: 25px;
  font-weight: bold;
  border: 1px solid blue;
}
```

# Using a Mixin

### The @include directive is used to include a mixin.

```scss
.danger {
  @include important-text;
  background-color: green;
}
```
