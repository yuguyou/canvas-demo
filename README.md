## sigma是什么?
 * 一个基于&lt;canvas>标签绘制点和线图形的JavaScript库，可使用canvas或webgl两种渲染器

## Linkurious
 * sigma的插件集

# &lt;canvas>标签:
  * getContext()  返回一个绘图对象
  * 调用getContext()获取canvas绘制图形的对象：参数‘2d’，‘webgl’
    ** getContext('webgl') 获取在画布上绘制三维图形的对象
    ** getContext('2d') 获取在画布上绘制二维图形的对象
  ```javascript
      var canvas = document.getElementById('new-canvas');
      var ctx = canvas.getContext('2d');
  ```
## Canvas
 * SVG:描述图形的XML语法            (可以通过移除相应元素改变图型)
 * Canvas:基于JavaScript的绘图API   (需要把当前的图形擦除再重绘图形来改变图形)
 * 通过调用canvas提供的方法通过构建XML元素来使用SVG绘制图形

## 方法属性：
## 文本
    * drawImage(img,x,y,width,height) 在画布上绘制载入图像
    * font() 设置文本内容和字体属性
    * fillStyle 绘画路径的颜色(填充)
    * fillText(text,x,y,maxWidth) 绘制文本
    * strokeStyle 绘画路径的颜色(非填充)
    * strokeText(text,x,y,maxWidth) 绘制文本
    * clearRect(x, y, width, height) 擦除给定矩形中的内容

### 图形
#### 直接绘出图形
    * lineWidth 描绘线条宽度
    * fillRect(x, y, width, height)  绘制矩形(被填充)
    * strokeRect(x, y, width, height) 绘制矩形（无填充）

#### 其他得基于路径绘制图形
    * beginPath() 开始或重置路径
    * rect(x,y,width,height) 只创建矩形路径
    * fill() 填充已定义路径
    * stroke() 绘制已定义的路径
    * moveTo(x, y) 指定或移动路径开始点
    * lineTo(x, y) 创建开始点到指点的路径
    * lineCap 线条末端线帽的样式
    * lineJoin 两线相交的形状
    * arc(x,y,r,sAngle,eAngle,counterclockwise) 创建圆弧路径

