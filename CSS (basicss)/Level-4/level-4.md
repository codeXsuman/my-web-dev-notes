

## Flexbox
`Flexible Box Layout`
*It is a one-dimensional layout method for arranging items in rows or columns.*
![img](/my-web-dev-notes/)
<!-- <img src="/my-web-dev-notes/CSS (basicss)/data/Screenshot_20250811-212324_Chrome.jpg" alt="img" width="300px"> -->

### **Flexbox Direction**
*It sets how flex items are placed in the flex container, along which axis and direction.*
* `flex-direction : row; (default)`
* `flex-direction : row-reverse;`
* `flex-direction : column;`
* `flex-direction : column-reverse;`

### **Flex Properties**
*for Flex Container*

* `justify-content : flex-start / flex-end / centre / space-evenly /` *(alignment along the main axis.)*
* `flex-wrap : nowrap / wrap / wrap-reverse`
* `align-items :`  *(alignment along the cross axis.)*
* `align-content :`  *(alignment of space between & around the content along cross-axis)*
* `align-self :` *(alignment of individual along the cross axis.)*
* `flex-grow :` *(how much a flex item will grow relative to the rest of the flex items if
space is available)*
* `flex-shrink :` *(how much a flex item will shrink relative to the rest of the flex items if
space is available)*

## Media Queries
*Help create a responsive website*
```css
@media (width:400px) {  /* bg-color will be red at 600px */
    div {
        background-color: red;
    }
}

@media (min-width:600px) { /* if width > 600px Bg-colour will be changed */
    div{
        background-color: chocolate;
    }
}

@media (min-width : 200px) and (max-width : 300px) {
    div {
        background-color : red;
    }
}
```
