---
title: LengthUnit
second_title: GroupDocs.Editor for Java API Reference
description: All supported length units
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

All supported length units

--------------------

[https://developer.mozilla.org/en-US/docs/Web/CSS/length\#Units][https_developer.mozilla.org_en-US_docs_Web_CSS_length_Units]


[https_developer.mozilla.org_en-US_docs_Web_CSS_length_Units]: https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units
## Fields

| Field | Description |
| --- | --- |
| [Unitless](#Unitless) | Unitless - no defined length unit. |
| [Px](#Px) | Pixel. |
| [Em](#Em) | Em. |
| [Ex](#Ex) | Ex (x-length). |
| [Cm](#Cm) | Cm. |
| [Mm](#Mm) | Mm. |
| [In](#In) | In. |
| [Pt](#Pt) | Pt. |
| [Pc](#Pc) | Pc. |
| [Ch](#Ch) | Ch. |
| [Rem](#Rem) | Rem. |
| [Vw](#Vw) | Vw - viewport width. |
| [Vh](#Vh) | Vh - viewport height. |
| [Vmin](#Vmin) | Vmin. |
| [Vmax](#Vmax) | Vmax. |
| [Percent](#Percent) | The value is relative to a fixed (external) value, that is context dependent. |
## Methods

| Method | Description |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Unitless - no defined length unit. Default value.

### Px {#Px}
```
public static final int Px
```


Pixel. Relative to the viewing device. For screen display, typically one device pixel (dot) of the display.

### Em {#Em}
```
public static final int Em
```


Em. This unit represents the calculated font-size of the element.

### Ex {#Ex}
```
public static final int Ex
```


Ex (x-length). This unit represents the x-height of the element's font. On fonts with the 'x' letter, this is generally the height of lowercase letters in the font; 1ex \\u2248 0.5em in many fonts.

### Cm {#Cm}
```
public static final int Cm
```


Cm. One centimeter (10 millimeters).

### Mm {#Mm}
```
public static final int Mm
```


Mm. One millimeter.

### In {#In}
```
public static final int In
```


In. One inch (2.54 centimeters).

### Pt {#Pt}
```
public static final int Pt
```


Pt. One point is 1/72th of an inch or 0.353 mm.

### Pc {#Pc}
```
public static final int Pc
```


Pc. One pica (12 points).

### Ch {#Ch}
```
public static final int Ch
```


Ch. This unit represents the width, or more precisely the advance measure, of the glyph '0' (zero, the Unicode character U+0030) in the element's font.

### Rem {#Rem}
```
public static final int Rem
```


Rem. This unit represents the font-size of the root element (e.g. the font-size of the <html> element). When used on the font-size on this root element, it represents its initial value.

### Vw {#Vw}
```
public static final int Vw
```


Vw - viewport width. 1/100th of the width of the viewport.

### Vh {#Vh}
```
public static final int Vh
```


Vh - viewport height. 1/100th of the height of the viewport.

### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100th of the minimum value between the height and the width of the viewport.

### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100th of the maximum value between the height and the width of the viewport.

### Percent {#Percent}
```
public static final int Percent
```


The value is relative to a fixed (external) value, that is context dependent. 1% = 1/100 of the external value.

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
