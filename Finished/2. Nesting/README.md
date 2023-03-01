# Nesting

## 👇 Sass lets you nest CSS selectors in the same way as HTML.

```scss
nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  li {
    display: inline-block;
  }
  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}
```

### 👆 Notice that in Sass, the ul, li, and a selectors are nested inside the nav selector.
