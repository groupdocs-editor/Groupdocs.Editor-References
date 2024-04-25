---
title: Length.Unit
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: All supported length units
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
**Inheritance:**
java.lang.Object
```
public static final class Length.Unit
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
public static final byte Unitless
```


Unitless - no defined length unit. Default value.

### Px {#Px}
```
public static final byte Px
```


Pixel. Relative to the viewing device. For screen display, typically one device pixel (dot) of the display.

### Em {#Em}
```
public static final byte Em
```


Em. This unit represents the calculated font-size of the element.

### Ex {#Ex}
```
public static final byte Ex
```


Ex (x-length). This unit represents the x-height of the element's font. On fonts with the 'x' letter, this is generally the height of lowercase letters in the font; 1ex \\u2248 0.5em in many fonts.

### Cm {#Cm}
```
public static final byte Cm
```


Cm. One centimeter (10 millimeters).

### Mm {#Mm}
```
public static final byte Mm
```


Mm. One millimeter.

### In {#In}
```
public static final byte In
```


In. One inch (2.54 centimeters).

### Pt {#Pt}
```
public static final byte Pt
```


Pt. One point is 1/72th of an inch or 0.353 mm.

### Pc {#Pc}
```
public static final byte Pc
```


Pc. One pica (12 points).

### Ch {#Ch}
```
public static final byte Ch
```


Ch. This unit represents the width, or more precisely the advance measure, of the glyph '0' (zero, the Unicode character U+0030) in the element's font.

### Rem {#Rem}
```
public static final byte Rem
```


Rem. This unit represents the font-size of the root element (e.g. the font-size of the <html> element). When used on the font-size on this root element, it represents its initial value.

### Vw {#Vw}
```
public static final byte Vw
```


Vw - viewport width. 1/100th of the width of the viewport.

### Vh {#Vh}
```
public static final byte Vh
```


Vh - viewport height. 1/100th of the height of the viewport.

### Vmin {#Vmin}
```
public static final byte Vmin
```


Vmin. 1/100th of the minimum value between the height and the width of the viewport.

### Vmax {#Vmax}
```
public static final byte Vmax
```


Vmax. 1/100th of the maximum value between the height and the width of the viewport.

### Percent {#Percent}
```
public static final byte Percent
```


The value is relative to a fixed (external) value, that is context dependent. 1% = 1/100 of the external value.

### getUnit() {#getUnit--}
```
public static byte[] getUnit()
```




**Returns:**
byte[]
### getUnits() {#getUnits--}
```
public static Map<Byte,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Byte,java.lang.String>
