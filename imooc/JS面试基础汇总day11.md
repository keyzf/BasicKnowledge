## JS为什么会阻碍页面加载？
因为JS能够改变DOM结构，为了防止冲突，所以要有一个先执行。

- - -
## 为什么要把CSS放在head中
因为方便渲染DOM树的时候已经知道样式直接进行渲染，不然还得产生重绘等不必要的重复计算。

- - -
## 为什么把JS放在最后
- 性能优化
- 保证DOM已经存在。防止JS操作一个还未渲染的DOM结构。

- - -
## 使用SSR后端渲染
不需要AJAX获取数据，可以从后端直接将数据渲染到页面。

