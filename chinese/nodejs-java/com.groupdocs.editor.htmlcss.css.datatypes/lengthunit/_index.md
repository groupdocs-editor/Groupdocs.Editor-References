---
title: "LengthUnit"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "所有支持的长度单位"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

所有支持的长度单位


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - 未定义长度单位。 |
|
|  | [Px](#Px) | 像素。 |
|
|  | [Em](#Em) | Em。 |
|
|  | [Ex](#Ex) | Ex（x 长度）。 |
|
|  | [Cm](#Cm) | Cm。 |
|
|  | [Mm](#Mm) | Mm。 |
|
|  | [In](#In) | In。 |
|
|  | [Pt](#Pt) | Pt。 |
|
|  | [Pc](#Pc) | Pc。 |
|
|  | [Ch](#Ch) | Ch。 |
|
|  | [Rem](#Rem) | Rem。 |
|
|  | [Vw](#Vw) | Vw - 视口宽度。 |
|
|  | [Vh](#Vh) | Vh - 视口高度。 |
|
|  | [Vmin](#Vmin) | Vmin。 |
|
|  | [Vmax](#Vmax) | Vmax。 |
|
|  | [Percent](#Percent) | 该值相对于固定（外部）值，即上下文 |
依赖。
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


无单位 - 未定义长度单位。默认值。


### Px {#Px}
```
public static final int Px
```


像素。相对于观看设备。对于屏幕显示，通常
显示器的一个设备像素（点）。


### Em {#Em}
```
public static final int Em
```


Em。此单位表示元素的计算后字体大小。


### Ex {#Ex}
```
public static final int Ex
```


Ex（x 长度）。此单位表示元素的 x 高度
字体。在包含字符 'x' 的字体中，这通常是
小写字母的高度；在许多字体中 1ex \\u2248 0.5em。


### Cm {#Cm}
```
public static final int Cm
```


Cm。1 厘米（10 毫米）。


### Mm {#Mm}
```
public static final int Mm
```


Mm。1 毫米。


### In {#In}
```
public static final int In
```


In。1 英寸（2.54 厘米）。


### Pt {#Pt}
```
public static final int Pt
```


Pt。1 磅等于英寸的 1/72 或 0.353 毫米。


### Pc {#Pc}
```
public static final int Pc
```


Pc。1 pica（12 磅）。


### Ch {#Ch}
```
public static final int Ch
```


Ch。此单位表示宽度，或更精确地说是前进
度量，字符 '0'（零，Unicode 字符 U+0030）在
元素的字体。


### Rem {#Rem}
```
public static final int Rem
```


Rem。此单位表示根元素的字体大小（例如
\<html\> 元素的字体大小）。当在字体大小上使用时
此根元素，它表示其初始值。


### Vw {#Vw}
```
public static final int Vw
```


Vw - 视口宽度。视口宽度的千分之一。


### Vh {#Vh}
```
public static final int Vh
```


Vh - 视口高度。视口高度的千分之一。


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin。高度和宽度之间最小值的千分之一
视口的。


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax。高度和宽度之间最大值的千分之一
视口的。


### Percent {#Percent}
```
public static final int Percent
```


该值相对于固定（外部）值，即上下文
依赖的。1% = 外部值的 1/100。


### getUnit() {#getUnit--}
```
public static Integer[] getUnit()
```




**Returns:**
java.lang.Integer[]
### getUnits() {#getUnits--}
```
public static Map<Integer,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
