---
title: "LengthUnit"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Все поддерживаемые единицы длины"
type: docs
weight: 13
url: /ru/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Все поддерживаемые единицы длины


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Поля

| Поле | Описание |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless — нет определённой единицы длины. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-length). |
|
|  | [Cm](#Cm) | Cm. |
|
|  | [Mm](#Mm) | Mm. |
|
|  | [In](#In) | In. |
|
|  | [Pt](#Pt) | Pt. |
|
|  | [Pc](#Pc) | Pc. |
|
|  | [Ch](#Ch) | Ch. |
|
|  | [Rem](#Rem) | Rem. |
|
|  | [Vw](#Vw) | Vw — ширина области просмотра. |
|
|  | [Vh](#Vh) | Vh - высота области просмотра. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Значение относительно фиксированного (внешнего) значения, то есть контекста |
зависящего.
|
## Методы

| Метод | Описание |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Без единицы измерения - нет определённой единицы длины. Значение по умолчанию.


### Px {#Px}
```
public static final int Px
```


Пиксель. Относительно устройства отображения. Для экранного вывода обычно
один пиксель устройства (точка) дисплея.


### Em {#Em}
```
public static final int Em
```


Em. Эта единица представляет рассчитанный размер шрифта элемента.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-длина). Эта единица представляет x-высоту элемента
шрифта. В шрифтах с буквой 'x' это обычно высота
строчных букв в шрифте; 1ex \\u2248 0.5em во многих шрифтах.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Один сантиметр (10 миллиметров).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Один миллиметр.


### In {#In}
```
public static final int In
```


In. Один дюйм (2,54 сантиметра).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Одна точка — 1/72 дюйма или 0,353 мм.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Один пайка (12 точек).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Эта единица представляет ширину, а точнее расстояние
продвижения глифа '0' (ноль, символ Unicode U+0030) в
шрифте элемента.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Эта единица представляет размер шрифта корневого элемента (например
размер шрифта элемента \<html\> элемент). Когда используется для размера шрифта
этого корневого элемента, он представляет его начальное значение.


### Vw {#Vw}
```
public static final int Vw
```


Vw - ширина области просмотра. 1/100 ширины области просмотра.


### Vh {#Vh}
```
public static final int Vh
```


Vh - высота области просмотра. 1/100 высоты области просмотра.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 от минимального значения между высотой и шириной
области просмотра.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 от максимального значения между высотой и шириной
области просмотра.


### Percent {#Percent}
```
public static final int Percent
```


Значение относительно фиксированного (внешнего) значения, то есть контекста
зависимый. 1% = 1/100 внешнего значения.


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
