碰撞检测-矩形边界检测法
====
- 检测两个矩形边框是否有相交，就可以判断出是否产生碰撞  
- 遍历所有已经存在的矩形，如果和当前活动的矩形产生碰撞，则把当前活动矩形放在与它碰撞的矩形上面

弹性碰撞检测-基于距离的检测法
- 适用于球类物体。先确定两物体间的最小距离，然后计算两物体的实际距离，若比最小距离还小，说明发生了碰撞。  
- 如果发生碰撞，则为球设置反向加速度，大小与碰撞程度成正比，即可造成“反弹”的效果。  
- 如果两个球都在运动，则各设置反向加速度的一半


![](https://github.com/lilyzhang728/canvas/blob/master/collision/img/demo.PNG)
![](https://github.com/lilyzhang728/canvas/blob/master/collision/img/demo1.PNG)
