---
title: "FontStyle"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "परिभाषित करता है कि फ़ॉन्ट को उसके फ़ॉन्ट‑फ़ैमिली से सामान्य, इटैलिक या ऑब्लिक फ़ेस के साथ कैसे स्टाइल किया जाना चाहिए।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

परिभाषित करता है कि फ़ॉन्ट को उसके फ़ॉन्ट‑फ़ैमिली से सामान्य, इटैलिक, या ऑब्लिक फ़ेस के साथ कैसे स्टाइल किया जाना चाहिए।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [Normal](#Normal) | फ़ॉन्ट‑फ़ैमिली के भीतर सामान्य रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। |
|
|  | [Italic](#Italic) | इटैलिक रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। |
|
|  | [Oblique](#Oblique) | ऑब्लिक रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isInitial()](#isInitial--) | बताता है कि इस फ़ॉन्ट‑स्टाइल का प्रारंभिक मान (Normal) है या नहीं। |
|
|  | [getValue()](#getValue--) | इस फ़ॉन्ट स्टाइल का मान स्ट्रिंग के रूप में लौटाता है। |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | निर्धारित करता है कि यह फ़ॉन्ट‑स्टाइल इंस्टेंस निर्दिष्ट के बराबर है या नहीं। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह फ़ॉन्ट‑स्टाइल इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं। |
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश‑कोड लौटाता है। |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | जाँचता है कि दो "FontStyle" मान समान हैं या नहीं। |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | जाँचता है कि दो "FontStyle" मान असमान हैं या नहीं। |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | निर्दिष्ट कीवर्ड को 'font-style' का उचित कीवर्ड मान पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है। |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


फ़ॉन्ट‑फ़ैमिली के भीतर सामान्य रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। प्रारंभिक मान।


### Italic {#Italic}
```
public static final FontStyle Italic
```


इटैलिक रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। यदि फ़ेस का इटैलिक संस्करण उपलब्ध नहीं है, तो इसके बजाय ऑब्लिक वर्गीकृत फ़ॉन्ट उपयोग किया जाता है। यदि दोनों उपलब्ध नहीं हैं, तो शैली को कृत्रिम रूप से सिम्युलेट किया जाता है।


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


ऑब्लिक रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। यदि फ़ेस का ऑब्लिक संस्करण उपलब्ध नहीं है, तो इसके बजाय इटैलिक वर्गीकृत फ़ॉन्ट उपयोग किया जाता है। यदि दोनों उपलब्ध नहीं हैं, तो शैली को कृत्रिम रूप से सिम्युलेट किया जाता है।


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


बताता है कि इस फ़ॉन्ट‑स्टाइल का प्रारंभिक मान (Normal) है या नहीं।


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


इस फ़ॉन्ट स्टाइल का मान स्ट्रिंग के रूप में लौटाता है।


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


निर्धारित करता है कि यह फ़ॉन्ट‑स्टाइल इंस्टेंस निर्दिष्ट के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | अन्य फ़ॉन्ट‑स्टाइल इंस्टेंस |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह फ़ॉन्ट‑स्टाइल इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अनकास्टेड font-style इंस्टेंस, संभवतः null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


जाँचता है कि दो "FontStyle" मान समान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | जाँचने के लिए पहला मान |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


जाँचता है कि दो "FontStyle" मान असमान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | जाँचने के लिए पहला मान |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो false, अन्यथा true

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


निर्दिष्ट कीवर्ड को 'font-style' का उचित कीवर्ड मान पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | कीवर्ड | java.lang.String | पार्स करने के लिए एक कीवर्ड |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | परिणाम, यदि पार्स सफल रहा, अन्यथा #Normal.Normal |
|

**Returns:**
boolean - यदि पार्स सफल रहा तो true, अन्यथा false

