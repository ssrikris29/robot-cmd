# robot-cmd
Automatically operate the keyboard and mouse, do not need gyp

## Example

```javascript
const robot = require('robot-cmd')

robot.moveTo(100,100)
robot.leftClick()
robot.rightClick()
robot.screenShot('./screenshot.png')
```

![robot.gif](./img/robot.gif)
