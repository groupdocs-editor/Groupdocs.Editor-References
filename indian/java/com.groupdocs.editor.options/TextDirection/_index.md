---
title: "TextDirection"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सादा पाठ दस्तावेज़ों में टेक्स्ट दिशा को संभालने के 3 संभावित विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 38
url: /hi/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

सादा पाठ में टेक्स्ट दिशा को संभालने के 3 संभावित विकल्पों का प्रतिनिधित्व करता है।
दस्तावेज़

## Fields

| Field | विवरण |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | बाएँ‑से‑दाएँ दिशा, सामान्य पाठ, डिफ़ॉल्ट मान। |
|
|  | [RightToLeft](#RightToLeft) | दाएँ‑से‑बाएँ दिशा |
|
|  | [Auto](#Auto) | दिशा का स्वतः पता लगाएँ। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


बाएँ‑से‑दाएँ दिशा, सामान्य पाठ, डिफ़ॉल्ट मान।


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


दाएँ‑से‑बाएँ दिशा


### Auto {#Auto}
```
public static final int Auto
```


दिशा का स्वतः पता लगाएँ। जब यह विकल्प चुना जाता है और पाठ में शामिल होता है
RTL लिपियों के अक्षर, तो दस्तावेज़ दिशा सेट की जाएगी
स्वचालित रूप से RTL में।


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
