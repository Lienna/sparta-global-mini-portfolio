# Sparta-global-mini-portfolio

## Introduction
Designing a web page using HTML and CSS and incorporating responsiveness to cater to different screen sizes.

### Method

### Positioning and Adjustments
Use the following code to align text, eg. to the center
```CSS
{
  text-align: center;
}
```

Use `float` to position sections on the page either to the left or right.
```CSS
.right {
  float: right;
```

Borders could be used to change pictures from a square format to a circle format.
```CSS
.hello {
  border-radius: 50%;
}
```

### Responsiveness
 Use media tags to determine what happens to sections of the document once screen size is adjusted. Specify the maximum width of the window at which the changes will apply.

```CSS
.left {
  float: left;
  font-size: 20px;
  margin: 50px;
  max-width: 500px;
  text-align: center;
}
```

```CSS
@media screen and (max-width:768px) {
  .left {
    float: none;
    font-size: 20px;
    margin: 50px;
    max-width: 500px;
    text-align: center;
  }
```
