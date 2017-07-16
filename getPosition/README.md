获取鼠标相对于canvas画布的位置
====

- 通过 e.clientX 和 e.clientY 可获得鼠标相对于视口的坐标  
- getBoundingClientRect()方法返回矩形对象，包括6个属性：left,top,right,bottom,width,height. 表示该元素相对于视口的位置，其中right指的元素右边
界距离窗口最左边的距离，bottom指的是元素下边界距离窗口最上边的距离。  
因此 canvas.getBoundingClientRect() 就可以返回画布的位置  
- 再分别作差，绑定到 mousemove 事件中，即可得到相对于画布的位置


![](https://github.com/lilyzhang728/canvas/blob/master/getPosition/img/demo.PNG)
