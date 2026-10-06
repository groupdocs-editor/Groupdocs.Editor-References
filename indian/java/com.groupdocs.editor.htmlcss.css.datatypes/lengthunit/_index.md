---
title: "LengthUnit"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित लंबाई इकाइयाँ"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

सभी समर्थित लंबाई इकाइयाँ


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Fields

| Field | विवरण |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - कोई परिभाषित लंबाई इकाई नहीं। |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-लंबाई). |
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
|  | [Vw](#Vw) | Vw - व्यूपोर्ट चौड़ाई। |
|
|  | [Vh](#Vh) | Vh - व्यूपोर्ट की ऊँचाई। |
|
|  | [Vmin](#Vmin) | Vmin। |
|
|  | [Vmax](#Vmax) | Vmax। |
|
|  | [Percent](#Percent) | मान एक निश्चित (बाहरी) मान के सापेक्ष है, जो संदर्भ है |
निर्भर।
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


बिना इकाई के - कोई परिभाषित लंबाई इकाई नहीं। डिफ़ॉल्ट मान।


### Px {#Px}
```
public static final int Px
```


पिक्सेल। दर्शक उपकरण के सापेक्ष। स्क्रीन डिस्प्ले के लिए, आमतौर पर
डिस्प्ले का एक डिवाइस पिक्सेल (डॉट)।


### Em {#Em}
```
public static final int Em
```


Em। यह इकाई तत्व के गणना किए गए फ़ॉन्ट‑साइज़ को दर्शाती है।


### Ex {#Ex}
```
public static final int Ex
```


Ex (x‑लंबाई)। यह इकाई तत्व की x‑ऊँचाई को दर्शाती है
फ़ॉन्ट। 'x' अक्षर वाले फ़ॉन्ट में, यह सामान्यतः ऊँचाई होती है
फ़ॉन्ट में छोटे अक्षरों की; कई फ़ॉन्ट में 1ex \\u2248 0.5em।


### Cm {#Cm}
```
public static final int Cm
```


Cm। एक सेंटीमीटर (10 मिलीमीटर)।


### Mm {#Mm}
```
public static final int Mm
```


Mm। एक मिलीमीटर।


### In {#In}
```
public static final int In
```


In। एक इंच (2.54 सेंटीमीटर)।


### Pt {#Pt}
```
public static final int Pt
```


Pt। एक पॉइंट इंच का 1/72 भाग या 0.353 मिमी है।


### Pc {#Pc}
```
public static final int Pc
```


Pc। एक पिका (12 पॉइंट)।


### Ch {#Ch}
```
public static final int Ch
```


Ch। यह इकाई चौड़ाई को दर्शाती है, या अधिक सटीक रूप से अग्रिम
माप, ग्लीफ़ '0' (शून्य, यूनिकोड कैरेक्टर U+0030) का
तत्व के फ़ॉन्ट का।


### Rem {#Rem}
```
public static final int Rem
```


Rem। यह इकाई रूट तत्व (जैसे
फ़ॉन्ट‑साइज़ \\<html\\> तत्व). जब फ़ॉन्ट‑साइज़ पर उपयोग किया जाता है
इस रूट तत्व में, यह उसकी प्रारंभिक मान को दर्शाता है।


### Vw {#Vw}
```
public static final int Vw
```


Vw - व्यूपोर्ट की चौड़ाई। व्यूपोर्ट की चौड़ाई का 1/100 हिस्सा।


### Vh {#Vh}
```
public static final int Vh
```


Vh - व्यूपोर्ट की ऊँचाई। व्यूपोर्ट की ऊँचाई का 1/100 हिस्सा।


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. ऊँचाई और चौड़ाई के बीच न्यूनतम मान का 1/100वाँ हिस्सा
व्यूपोर्ट का।


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. ऊँचाई और चौड़ाई के बीच अधिकतम मान का 1/100वाँ हिस्सा
व्यूपोर्ट का।


### Percent {#Percent}
```
public static final int Percent
```


मान एक निश्चित (बाहरी) मान के सापेक्ष है, जो संदर्भ है
dependent. 1% = बाहरी मान का 1/100।


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
