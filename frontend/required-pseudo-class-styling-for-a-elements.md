# Required Pseudo Class Styling for <a> Elements

For <a> links we need only three state's: default, :hover, and active. 

Here is an example for a simple link:

```css
a {
    color: var(--primary-color);
}

a:hover {
    color: var(--primary-color-dark);
}
a:active {
    color: var(--primary-color-light);
}
```

Here's an example for a sampe <a> element that has the class "button":
```css
a.button {
    color: var(--primary-color);
}

a.button:hover {
    color: var(--primary-color-dark);
}
a.button:active {
    color: var(--primary-color-light);
}
```