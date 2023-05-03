# framer-motion_notes

### Install framer motion
```npm
npm i framer-motion
```

### Animate a component
 ```javascript
 import {motion} from 'framer-motion'
 ```
 
 ```html
 <motion.div></motion.div>
 ```

### Animating a compnent
```html
<motion.h2 animate = {{}}>Some text</motion.h2>
```

### transform:translate propery in CSS animation in framer motion will be, 
```html
<motion.h2 animate={{x:2, y:3}}>Some text</motion.h2> 
<!-- x and y in traditional CSS are: translateX and translateY -->
```

