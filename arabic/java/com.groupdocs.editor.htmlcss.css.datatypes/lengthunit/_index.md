---
title: "LengthUnit"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "جميع وحدات الطول المدعومة"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

جميع وحدات الطول المدعومة


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Unitless](#Unitless) | بدون وحدة - لا توجد وحدة طول معرفة. |
|
|  | [Px](#Px) | بكسل. |
|
|  | [Em](#Em) | إم. |
|
|  | [Ex](#Ex) | إكس (طول س). |
|
|  | [Cm](#Cm) | سم. |
|
|  | [Mm](#Mm) | مم. |
|
|  | [In](#In) | إنش. |
|
|  | [Pt](#Pt) | نقطة. |
|
|  | [Pc](#Pc) | بيكا. |
|
|  | [Ch](#Ch) | حرف. |
|
|  | [Rem](#Rem) | ريم. |
|
|  | [Vw](#Vw) | Vw - عرض مساحة العرض. |
|
|  | [Vh](#Vh) | Vh - ارتفاع نافذة العرض. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | القيمة نسبية إلى قيمة ثابتة (خارجية)، وهذا هو السياق |
معتمد.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


بدون وحدة - لا توجد وحدة طول معرفة. القيمة الافتراضية.


### Px {#Px}
```
public static final int Px
```


بكسل. نسبية إلى جهاز العرض. للعرض على الشاشة، عادةً
بكسل واحد (نقطة) من شاشة العرض.


### Em {#Em}
```
public static final int Em
```


Em. تمثل هذه الوحدة حجم الخط المحسوب للعنصر.


### Ex {#Ex}
```
public static final int Ex
```


Ex (طول-x). تمثل هذه الوحدة الارتفاع-x للعنصر
الخط. في الخطوط التي تحتوي على الحرف 'x'، يكون هذا عادةً ارتفاع
الأحرف الصغيرة في الخط؛ 1ex \\u2248 0.5em في العديد من الخطوط.


### Cm {#Cm}
```
public static final int Cm
```


سم. سنتيمتر واحد (10 مليمترات).


### Mm {#Mm}
```
public static final int Mm
```


مم. مليمتر واحد.


### In {#In}
```
public static final int In
```


إنش. بوصة واحدة (2.54 سنتيمتر).


### Pt {#Pt}
```
public static final int Pt
```


نقطة. نقطة واحدة هي 1/72 من البوصة أو 0.353 مم.


### Pc {#Pc}
```
public static final int Pc
```


بيكا. بيكا واحدة (12 نقطة).


### Ch {#Ch}
```
public static final int Ch
```


Ch. تمثل هذه الوحدة العرض، أو بدقة أكبر التقدم
القياس، للرمز '0' (صفر، حرف يونيكود U+0030) في
خط العنصر.


### Rem {#Rem}
```
public static final int Rem
```


Rem. تمثل هذه الوحدة حجم الخط للعنصر الجذر (مثلاً
حجم الخط لعنصر \<html\>). عندما يُستخدم على حجم الخط في
هذا العنصر الجذر، فإنه يمثل قيمته الأولية.


### Vw {#Vw}
```
public static final int Vw
```


Vw - عرض نافذة العرض. 1/100 من عرض نافذة العرض.


### Vh {#Vh}
```
public static final int Vh
```


Vh - ارتفاع نافذة العرض. 1/100 من ارتفاع نافذة العرض.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 من القيمة الدنيا بين الارتفاع والعرض
من نافذة العرض.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 من القيمة القصوى بين الارتفاع والعرض
من نافذة العرض.


### Percent {#Percent}
```
public static final int Percent
```


القيمة نسبية إلى قيمة ثابتة (خارجية)، وهذا هو السياق
معتمد. 1% = 1/100 من القيمة الخارجية.


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
