# mycanvas
这里是我做自己的canvas作品，好好学习canvas！
做个说明，工具里的utils.js的代码来自于妙味课堂~避个嫌，非广告

# canvas中需要用到的各种公式：
1、角度与弧度：<br />
        180度 = π弧度<br />
        1弧度 = (π/180) * 度<br />
        1度 = (180/π) * 弧度<br/>
2、canvas坐标系中求角度：<br />
        dx = mouse.x - W/2
        dy = mouse.y - W/2
        angle = Math.atan2(dy,dx) * 180 / Math.PI