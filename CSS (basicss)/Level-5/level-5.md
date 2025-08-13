# <p align="center"> Transitions </p>
***Transitions enable you to define the transition between two states of an element.***

* **transition-property :** property you want to transition (font-size, width etc.)

* **transition-duration :** 2s / 4ms ..

* **transition-timing-function :** ease-in / ease-out / linear / steps ..
* **transition-delay :** 2s / 4ms ..

## Transition Shorthand

*property name | duration | timing-function | delay*

* `transition: font-size 2s ease-in-out 0.2s;`

## <p align="center">CSS Transform</p>
*Used to apply 2D & 3D transformations to an element*

* **rotate**
  * `rotate(45deg);`

* **scale**
  * `transform:scale(2);`
  * `transform:scale(0.5);`
  * `transform:scale(1,2);`
  * `transform:scaleX(0.5)`
  * `transform:scaleY(0.5)`

* **translate**
  * `transform: translate(20px);`
  * `transform: translate(20px, 50px);`
  * `transform: translateX(20px);`
  * `transform: translateY(20px);`

* **skew**
  * `transform: skew(30deg);`

# <p align="center"> Animation </p>
***to animate CSS elements***

```css
@keyframe myName {
from { font-size : 20px; }
to { font-size : 40px; }
}
```

## Animation Properties

* animation-name
* animation-duration
* animation-timing-function
* animation-delay
* animation-iteration-count
* animation-direction

## Animation Shorthand
* `animation : myName 2s linear 3s infinite normal`

## % in Animation
```css
@keyframe myName {
0% { font-size : 20px; }
50% { font-size : 30px; }
100% { font-size : 40px; }
}
```


---