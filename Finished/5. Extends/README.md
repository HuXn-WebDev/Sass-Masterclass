# Sass @extend Directive

### The @extend directive lets you share a set of CSS properties from one selector to another.

### The @extend directive is useful if you have almost identically styled elements that only differ in some small details.

```scss
.button-basic {
  border: none;
  padding: 15px 30px;
  text-align: center;
  font-size: 16px;
  cursor: pointer;
}

.button-report {
  @extend .button-basic;
  background-color: red;
}

.button-submit {
  @extend .button-basic;
  background-color: green;
  color: white;
}
```
