---
title: "FontSize"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "फ़ॉन्ट आकार को एक विशेष इकाई या लंबाई मान के रूप में दर्शाता है जो फ़ॉन्ट का आकार निर्दिष्ट करता है, ऐतिहासिक रूप से बड़े अक्षर M की चौड़ाई के अनुसार।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

फ़ॉन्ट आकार को एक विशेष इकाई या लंबाई मान के रूप में दर्शाता है, जो फ़ॉन्ट का आकार निर्दिष्ट करता है (ऐतिहासिक रूप से बड़े अक्षर "M" की चौड़ाई)।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [Medium](#Medium) | मध्यम आकार। |
|
|  | [XxSmall](#XxSmall) | बहुत छोटा absolute-size |
|
|  | [XSmall](#XSmall) | औसत छोटा absolute-size |
|
|  | [Small](#Small) | सामान्य रूप से छोटा absolute-size |
|
|  | [Large](#Large) | सामान्य रूप से बड़ा absolute-size |
|
|  | [XLarge](#XLarge) | औसत बड़ा absolute-size |
|
|  | [XxLarge](#XxLarge) | बहुत बड़ा absolute-size |
|
|  | [Larger](#Larger) | बड़ा relative-size - फ़ॉन्ट पैरेंट एलिमेंट के font-size की तुलना में बड़ा होगा, लगभग उसी अनुपात से जो ऊपर के absolute-size कीवर्ड्स को अलग करता है। |
|
|  | [Smaller](#Smaller) | छोटा relative-size - फ़ॉन्ट पैरेंट एलिमेंट के font-size की तुलना में छोटा होगा, लगभग उसी अनुपात से जो ऊपर के absolute-size कीवर्ड्स को अलग करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isInitial()](#isInitial--) | सूचित करता है कि इस font-size का प्रारंभिक मान (Medium) है या नहीं |
|
|  | [getValue()](#getValue--) | इस font size का मान स्ट्रिंग के रूप में लौटाता है |
|
|  | [isLengthDefined()](#isLengthDefined--) | यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ एक [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) मान के साथ परिभाषित है या नहीं |
|
|  | [getLength()](#getLength--) | एक लंबाई मान, यदि यह फ़ॉन्ट‑साइज़ इसके साथ परिभाषित किया गया हो, अन्यथा अपवाद फेंका जाता है |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ उपयोगकर्ता के डिफ़ॉल्ट फ़ॉन्ट आकार (जो मध्यम है) के आधार पर एक निरपेक्ष आकार को कीवर्ड के रूप में परिभाषित है या नहीं |
|
|  | [isRelativeSize()](#isRelativeSize--) | यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ एक सापेक्ष आकार को कीवर्ड के रूप में परिभाषित है या नहीं। |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | निर्धारित करता है कि यह फ़ॉन्ट‑साइज़ उदाहरण निर्दिष्ट के बराबर है या नहीं |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह फ़ॉन्ट‑साइज़ उदाहरण निर्दिष्ट अनकास्टेड के बराबर है या नहीं |
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश‑कोड लौटाता है। |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Checks whether two "FontSize" values are equal |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Checks whether two "FontSize" values are not equal |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | निर्दिष्ट लंबाई से एक फ़ॉन्ट‑साइज़ बनाता है |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | निर्दिष्ट कीवर्ड को 'font-size' का उचित कीवर्ड मान पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है। |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


मध्यम आकार। प्रारंभिक मान।


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


बहुत छोटा absolute-size


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


औसत छोटा absolute-size


### Small {#Small}
```
public static final FontSize Small
```


सामान्य रूप से छोटा absolute-size


### Large {#Large}
```
public static final FontSize Large
```


सामान्य रूप से बड़ा absolute-size


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


औसत बड़ा absolute-size


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


बहुत बड़ा absolute-size


### Larger {#Larger}
```
public static final FontSize Larger
```


बड़ा relative-size - फ़ॉन्ट पैरेंट एलिमेंट के font-size की तुलना में बड़ा होगा, लगभग उसी अनुपात से जो ऊपर के absolute-size कीवर्ड्स को अलग करता है।


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


छोटा relative-size - फ़ॉन्ट पैरेंट एलिमेंट के font-size की तुलना में छोटा होगा, लगभग उसी अनुपात से जो ऊपर के absolute-size कीवर्ड्स को अलग करता है।


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


सूचित करता है कि इस font-size का प्रारंभिक मान (Medium) है या नहीं


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


इस font size का मान स्ट्रिंग के रूप में लौटाता है


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ एक [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) मान के साथ परिभाषित है या नहीं


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


एक लंबाई मान, यदि यह फ़ॉन्ट‑साइज़ इसके साथ परिभाषित किया गया हो, अन्यथा अपवाद फेंका जाता है


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ उपयोगकर्ता के डिफ़ॉल्ट फ़ॉन्ट आकार (जो मध्यम है) के आधार पर एक निरपेक्ष आकार को कीवर्ड के रूप में परिभाषित है या नहीं


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


यह दर्शाता है कि यह फ़ॉन्ट‑साइज़ एक सापेक्ष आकार को कीवर्ड के रूप में परिभाषित है या नहीं। फ़ॉन्ट पैरेंट तत्व के फ़ॉन्ट आकार की तुलना में बड़ा या छोटा होगा, लगभग उसी अनुपात से जो निरपेक्ष‑आकार कीवर्ड को अलग करता है।


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


निर्धारित करता है कि यह फ़ॉन्ट‑साइज़ उदाहरण निर्दिष्ट के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | अन्य फ़ॉन्ट‑साइज़ उदाहरण |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह फ़ॉन्ट‑साइज़ उदाहरण निर्दिष्ट अनकास्टेड के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य अनकास्टेड फ़ॉन्ट‑साइज़ उदाहरण, null हो सकता है |
|

**Returns:**
boolean - यदि समान हों तो true, यदि असमान हों, null या अन्य प्रकार के हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश‑कोड लौटाता है।


**Returns:**
int - Hash-code एक साइन किए हुए पूर्णांक के रूप में

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Checks whether two "FontSize" values are equal


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | जाँचने के लिए पहला मान |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Checks whether two "FontSize" values are not equal


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | जाँचने के लिए पहला मान |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो false, अन्यथा true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


निर्दिष्ट लंबाई से एक फ़ॉन्ट‑साइज़ बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | एक लंबाई मान, बिना इकाई के या नकारात्मक नहीं हो सकता |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


निर्दिष्ट कीवर्ड को 'font-size' का उचित कीवर्ड मान पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | कीवर्ड | java.lang.String | पार्स करने के लिए एक कीवर्ड |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | परिणाम, पार्सिंग सफल रहा, अन्यथा #Medium.Medium |
|

**Returns:**
boolean - यदि पार्स सफल रहा तो true, अन्यथा false

