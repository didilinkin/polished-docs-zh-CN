# polished-docs-zh-CN
polished 中文方法目录

<details open>
  <summary>Mixins - 混合</summary>
  <ul>
    <li>
      <a href="http://polished.js.org/docs/#clearfix">clearFix</a>
      <span> - 清理浮动 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#ellipsis">ellipsis</a>
      <span> - 将超过指定长度的文本，使用省略号替代 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#fontface">fontFace</a>
      - 字体库引入( 字体名称, 静态文件相对路径 )
    </li>
    <li>
      <a href="http://polished.js.org/docs/#hidpi">hiDPI</a>
      <span> - 指定高分屏样式 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#hidetext">hideText</a>
      <span> - 用于隐藏文本，显示图片 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#normalize">normalize</a>
      <span> - 样式表初始化 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#placeholder">placeholder</a>
      <span> - 对 placeholder 伪元素设置样式 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#radialgradient">radialGradient</a>
      - 径向渐变
    </li>
    <li>
      <a href="http://polished.js.org/docs/#retinaimage">retinaImage</a>
      <span> - 为高分屏和低分屏设置不同的背景图 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#selection">selection</a>
      <span> - 对 selection 伪元素设置样式 </span>
    </li>
    <li>
      <a href="http://polished.js.org/docs/#timingfunctions">timingFunctions</a>
      - 定时器函数( 处理动画 )
    </li>
    <li>
      <a href="http://polished.js.org/docs/#triangle">triangle</a>
      - 以CSS来创建三角形, 以及它的背景色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#wordwrap">wordWrap</a>
      - 简单的文字包装属性混合( 填写一个属性值 => 填写三个属性的属性值 )
    </li>
  </ul>
</details>
<details open>
  <summary>Color - 颜色</summary>
  <ul>
    <li>
      <a href="http://polished.js.org/docs/#adjusthue">adjustHue</a>
      - 改变颜色的方法。色相是0到360之间的数。第一个参数是颜色在色轮上旋转的程度, 后面是要改变的颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#complement">complement</a>
      - 返回互补色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#darken">darken</a>
      - 调节颜色深浅
    </li>
    <li>
      <a href="http://polished.js.org/docs/#desaturate">desaturate</a>
      - 降低颜色的饱和度
    </li>
    <li>
      <a href="http://polished.js.org/docs/#grayscale">grayscale</a>
      - 将一个颜色转为灰度
    </li>
    <li>
      <a href="http://polished.js.org/docs/#hsl">hsl</a>
      - 指定色调、饱和度和亮度三个值，返回一个颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#hsla">hsla</a>
      - 指定色调、饱和度、亮度和透明度三个值，返回一个颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#invert">invert</a>
      - 反转一个颜色的rgb(红绿蓝)三个值
    </li>
    <li>
      <a href="http://polished.js.org/docs/#lighten">lighten</a>
      - 调节颜色深浅
    </li>
    <li>
      <a href="http://polished.js.org/docs/#mix">mix</a>
      - 混合两种颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#opacify">opacify</a>
      - 调节透明度
    </li>
    <li>
      <a href="http://polished.js.org/docs/#parsetohsl">parseToHsl</a>
      - 返回一个HslColor或HslaColor对象
    </li>
    <li>
      <a href="http://polished.js.org/docs/#parsetorgb">parseToRgb</a>
      - 返回RgbColor或RgbaColor对象
    </li>
    <li>
      <a href="http://polished.js.org/docs/#rgb">rgb</a>
      - 指定红、绿、蓝三个值，返回一个颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#rgba">rgba</a>
      指定红、绿、蓝和透明度四个值，返回一个颜色
    </li>
    <li>
      <a href="http://polished.js.org/docs/#saturate">saturate</a>
      - 增加颜色的饱和度
    </li>
    <li>
      <a href="http://polished.js.org/docs/#sethue">setHue</a>
      - 输入色相值(01-359) 和一个想要配置的值; 返回计算好的颜色值
    </li>
    <li><a href="http://polished.js.org/docs/#setlightness">setLightness</a></li>
    <li><a href="http://polished.js.org/docs/#setsaturation">setSaturation</a></li>
    <li><a href="http://polished.js.org/docs/#shade">shade</a></li>
    <li><a href="http://polished.js.org/docs/#tint">tint</a></li>
    <li><a href="http://polished.js.org/docs/#transparentize">transparentize</a></li>
  </ul>
</details>
<details open>
  <summary>Shorthands - 简写方法</summary>
  <ul>
    <li>
      <a href="http://polished.js.org/docs/#animation">animation</a>
      - 简写动画属性(支持多动画, 以数组形式传入)
    </li>
    <li>
      <a href="http://polished.js.org/docs/#backgroundimages">backgroundImages</a>
      - 简写背景图属性(默认第一个参数为背景图参数, 第二个参数可以传入线性渐变)
    </li>
    <li>
      <a href="http://polished.js.org/docs/#backgrounds">backgrounds</a>
      - 简写的背景属性
    </li>
    <li>
      <a href="http://polished.js.org/docs/#bordercolor">borderColor</a>
      - 边框色的简写接受四个值，包括null，以跳过一个值
    </li>
    <li>
      <a href="http://polished.js.org/docs/#borderradius">borderRadius</a>
      - 边界半径的简写接受了边值和半径的值，并将半径值应用到这一边的两个角上
    </li>
    <li>
      <a href="http://polished.js.org/docs/#borderstyle">borderStyle</a>
      - 边框样式的简写(接受4个值), 可用null跳过一个值
    </li>
    <li>
      <a href="http://polished.js.org/docs/#borderwidth">borderWidth</a>
      - border 4个方向的width简写(上右下左), 可用null忽略某个值
    </li>
    <li>
      <a href="http://polished.js.org/docs/#buttons">buttons</a>
      - 填充所有按钮的选择器. 您可以通过可选的状态来附加到选择器
    </li>
    <li>
      <a href="http://polished.js.org/docs/#margin">margin</a>
      - margin缩写(4个)
    </li>
    <li>
      <a href="http://polished.js.org/docs/#padding">padding</a>
      - padding缩写(4个)
    </li>
    <li>
      <a href="http://polished.js.org/docs/#position">position</a>
      - position的简写方法, 可使用null跳过一个值, 方向为(上右下左), 第一个值可以设为position关键字
    </li>
    <li>
      <a href="http://polished.js.org/docs/#size">size</a>
      - 简写 高度和宽度(width & height)
    </li>
    <li>
      <a href="http://polished.js.org/docs/#textinputs">textInputs</a>
      - 填充所有文本输入的选择器。您可以通过可选的状态来附加到选择器
    </li>
    <li>
      <a href="http://polished.js.org/docs/#transitions">transitions</a>
      - 转换的简写接受任意数量的转换值作为创建一个转换语句的参数
    </li>
  </ul>
</details>
<details open>
  <summary>Helpers - 辅助对象</summary>
  <ul>
    <li>
      <a href="http://polished.js.org/docs/#directionalproperty">directionalProperty</a>
      - 定向设置(可传入margin 或者 padding), 然后四个方向的值也传入(不需要的方向用空字符串省略; 方向为: 上右下左);
    </li>
    <li>
      <a href="http://polished.js.org/docs/#em">em</a>
      - 将像素转为 em
    </li>
    <li>
      <a href="http://polished.js.org/docs/#modularscale">modularScale</a>
      - 调节比例
    </li>
    <li>
      <a href="http://polished.js.org/docs/#rem">rem</a>
      - 将像素转为 rem
    </li>
    <li>
      <a href="http://polished.js.org/docs/#stripunit">stripUnit</a>
      - 去除单位: 输入一个带单位的属性值; 返回去除单位的值(比如输入'10px', 返回'10')
    </li>
  </ul>
</details>
<details open>
  <summary>Types - 类型</summary>
  <ul>
    <li><a href="http://polished.js.org/docs/#animationproperty">AnimationProperty</a></li>
    <li><a href="http://polished.js.org/docs/#buttonstate">ButtonState</a></li>
    <li><a href="http://polished.js.org/docs/#fontfaceconfiguration">FontFaceConfiguration</a></li>
    <li><a href="http://polished.js.org/docs/#hslcolor">HslColor</a></li>
    <li><a href="http://polished.js.org/docs/#hslacolor">HslaColor</a></li>
    <li><a href="http://polished.js.org/docs/#inputstate">InputState</a></li>
    <li><a href="http://polished.js.org/docs/#pointingdirection">PointingDirection</a></li>
    <li><a href="http://polished.js.org/docs/#radialgradientconfiguration">RadialGradientConfiguration</a></li>
    <li><a href="http://polished.js.org/docs/#ratio">Ratio</a></li>
    <li><a href="http://polished.js.org/docs/#rgbacolor">RgbaColor</a></li>
    <li><a href="http://polished.js.org/docs/#rgbcolor">RgbColor</a></li>
    <li><a href="http://polished.js.org/docs/#timingfunction">TimingFunction</a></li>
    <li><a href="http://polished.js.org/docs/#tocolorstring">toColorString</a></li>
  </ul>
</details>
