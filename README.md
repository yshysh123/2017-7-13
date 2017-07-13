# 2017-7-13
第二天-上传点什么呢？来个CSS3的翻书效果吧

本例子使用纯CSS3的代码，没有用JS。

通过CSS3的3D，以及角度变化，角度旋转基点，以及动画实现。

使用本例子需要一些CSS3的技术。

1、preserve-3d   创建3D空间

      transform-style 属性规定如何在 3D 空间中呈现被嵌套的元素。
  
2、transform: rotate()

     Transform属性应用于元素的2D或3D转换。这个属性允许你将元素旋转，缩放，移动，倾斜等。
  
      值	        描述

      none	定义不进行转换。

      matrix(n,n,n,n,n,n)	定义 2D 转换，使用六个值的矩阵。

      matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n)	定义 3D 转换，使用 16 个值的 4x4 矩阵。

      translate(x,y)	定义 2D 转换。

      translate3d(x,y,z)	定义 3D 转换。

      translateX(x)	定义转换，只是用 X 轴的值。

      translateY(y)	定义转换，只是用 Y 轴的值。

      translateZ(z)	定义 3D 转换，只是用 Z 轴的值。

      scale(x[,y]?)	定义 2D 缩放转换。

      scale3d(x,y,z)	定义 3D 缩放转换。

      scaleX(x)	通过设置 X 轴的值来定义缩放转换。

      scaleY(y)	通过设置 Y 轴的值来定义缩放转换。

      scaleZ(z)	通过设置 Z 轴的值来定义 3D 缩放转换。

      rotate(angle)	定义 2D 旋转，在参数中规定角度。

      rotate3d(x,y,z,angle)	定义 3D 旋转。

      rotateX(angle)	定义沿着 X 轴的 3D 旋转。

      rotateY(angle)	定义沿着 Y 轴的 3D 旋转。

      rotateZ(angle)	定义沿着 Z 轴的 3D 旋转。

      skew(x-angle,y-angle)	定义沿着 X 和 Y 轴的 2D 倾斜转换。

      skewX(angle)	定义沿着 X 轴的 2D 倾斜转换。

      skewY(angle)	定义沿着 Y 轴的 2D 倾斜转换。

      perspective(n)	为 3D 转换元素定义透视视图。
  
3、animation

      animation 属性是一个简写属性，用于设置六个动画属性：

      animation-name

      animation-duration

      animation-timing-function

      animation-delay

      animation-iteration-count

      animation-direction

      注释：请始终规定 animation-duration 属性，否则时长为 0，就不会播放动画了
