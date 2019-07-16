主要用于记录开发过程中的一些积累，封装一些常用工具

# WDSignatureCanvas（iOS涂鸦封装）
大多数涂鸦都是用一次或二次贝塞尔曲线实现的，并通过drawRect或者shapeLayer绘制，无法实现笔锋效果，而OpenGL ES有太复杂，所以自己参考了很多代码库，用二次贝塞尔曲线算法取点，根据速度计算点的大小，最终通过画椭圆的方式，实现笔锋， 效果图下：
![](https://github.com/qq510304723/CommonUtils/blob/resource/signaturecanvas.gif?raw=true)


