# Partials

### Sass keeps the CSS code DRY (Don't Repeat Yourself). One way to write DRY code is to keep related code in separate files. You can create small files with CSS snippets to include in other Sass files. Examples of such files can be: reset file, variables, colors, fonts, font-sizes, etc.

### 👇 The @import directive allows you to include the content of one file in another.

```scss
@import "variables";
@import "colors";
@import "reset";
```
