# framer-motion_notes

### Install framer motion
```npm
npm i framer-motion
```




### Motion component: necessary to animate an element
 ```javascript
 import {motion} from 'framer-motion'

<motion.div></motion.div>
 ```




### Animate an element using the animate attribute
```javascript
<motion.h2 animate = {{}}>Some text</motion.h2>
```
The animate attribute accepts an object that contains all the animation properties like fontSize for increasing/decreasing the size of the text, color for animating the color of the text etc...




### Moving the motion elements
```javascript
<motion.h2 animate={{x:<positiveValue>}}>...</motion.h2> /* Positive value moves the element to the right*/
<motion.h2 animate={{x:<negetiveValue>}}>...</motion.h2> /* Negetive value moves the element to the left*/

<motion.h2 animate={{y:<positiveValue>}}>...</motion.h2> /* Positive value moves the element down*/
<motion.h2 animate={{y:<negetiveValue>}}>...</motion.h2> /* Negetive value moves the element up*/
```




### Scale up an element
```javascript
<motion.button animate={{scale:<neumericValue>}}></motion.button> /* The element will increase <neumaricValue> times its original size*/
```
