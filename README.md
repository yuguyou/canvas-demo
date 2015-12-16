##sigma是什么?
 * 一个基于&lt;canvas>标签绘制点和线图形的JavaScript库，可使用canvas或webgl两种渲染器
##Linkurious
 * sigma的插件集

# Canvas
 * SVG:描述图形的XML语法            (可以通过移除相应元素改变图型)
 * Canvas:基于JavaScript的绘图API   (需要把当前的图形擦除再重绘图形来改变图形)
 * 通过调用canvas提供的方法通过构建XML元素来使用SVG绘制图形

# &lt;canvas>标签:
  * getContext()  返回一个绘图对象
  * 调用getContext()获取canvas绘制图形的对象：参数‘2d’，‘webgl’
    * getContext('webgl') 获取在画布上绘制三维图形的对象
    * getContext('2d') 获取在画布上绘制二维图形的对象


