
## **Units in CSS**
*Relative*
* `%`
* `em`
* `rem`

### Percentage (%)
*It is often used to define a size as relative to an element's parent object.*
* `width : 33% ;`
* `margin-left : 50% ;`

### em
*font will be x times of its parent element. if parent element's font-size 10px & child element font size 2em --> means 20px*

### rem (root em)
*font size if the root element*

## Others

* vh: relative to 1% viewport height (my browser's height)
* vw : relative to 1% viewport width (my browser's width)

## Position
*The position CSS property sets how an element is positioned in a document.*
* `position : static / relative /absolute/ fixed`

**static -** default position (The top, right, bottom, left, and z-index properties have no effect)

**relative -** element is relative to itself. (The top, right, bottom, left, and z-index will work)

**absolute -** positioned relative to its closest positioned ancestor. (removed from the flow)

**fixed -** positioned relative to browser. (removed from flow)

**sticky -** positioned based on user's scroll position

## z-index

*It decides the stack level of elements.*
*Overlapping elements with a larger z-index cover those with a smaller one.*

* `z-index : auto (0)`
* `z-index : 1 / 2 / ...`
* `z-index : -1 / -2 / ...`

## Background Image
*Used to set an image as background*
* `background-image : url("image.jpeg");`

## Background Size
* `background-size : cover / contain / auto`

