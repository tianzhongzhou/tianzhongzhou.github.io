#css3

####css3基本属性

#####缩放

transform: scale(2);
2为缩放的倍数； 可放初识状态也可在hover状态 
#####旋转
```transform: rotate(45deg);
<!-- (旋转度数，两个状态都可) -->
transform-origin: left top;
<!-- 旋转的原点设置 -->
```
#####移位

```translate()
<!-- 只指定一个值x轴有位移；两个值分别为xy轴 -->
translateY()
<!-- 也可单独指定值 -->
<!-- 值为负数为反方向位移 -->
```
#####过渡效果 在原属性里加，不是在hover里
```
transition: transform 5s;
<!-- 控制hover里的属性的过渡时间 -->
<!-- 多种属性同时用时，用","分隔 -->
transition: transform 5s,backgound-color: #fff;
```
#####贝塞尔曲线 常用函数： ease---先快后慢； linner---匀速； ease-in---加速，渐显效果； ease-out---减速，渐隐效果； ease-in-out---先加速再减速，渐显渐隐效果
```
<!-- 在这些函数后加秒数有延迟作用 -->
<!-- 用这些函数用空格分隔，不是"，"号 -->
```
#####设置透明度。。
```
opacity: 0.5;
<!-- 值越小越透明 -->
```