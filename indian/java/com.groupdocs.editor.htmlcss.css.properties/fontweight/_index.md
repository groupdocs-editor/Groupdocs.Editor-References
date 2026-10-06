---
title: "FontWeight"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "Font-weight प्रॉपर्टी फ़ॉन्ट का वजन या मोटाई निर्धारित करती है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight प्रॉपर्टी फ़ॉन्ट का वजन (या मोटाई) निर्धारित करती है। उपलब्ध वजन वर्तमान में सेट किए गए फ़ॉन्ट‑फ़ैमिली पर निर्भर करते हैं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [Lighter](#Lighter) | पैरेंट तत्व से एक सापेक्ष फ़ॉन्ट वजन हल्का |
|
|  | [Bolder](#Bolder) | पैरेंट तत्व से एक सापेक्ष फ़ॉन्ट वजन भारी |
|
|  | [Normal](#Normal) | सामान्य फ़ॉन्ट वजन। |
|
|  | [Bold](#Bold) | बोल्ड फ़ॉन्ट वजन। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isInitial()](#isInitial--) | सूचित करता है कि इस font-size का प्रारंभिक मान (Medium) है या नहीं |
|
|  | [getNumber()](#getNumber--) | एक संख्या लौटाता है - 1 से 1000 के बीच पूर्णांक मान, जो फ़ॉन्ट की मोटाई का वर्णन करता है, या अपवाद फेंकता है, यदि वर्तमान मोटाई निरपेक्ष नहीं बल्कि सापेक्ष है। |
|
|  | [isAbsolute()](#isAbsolute--) | यह दर्शाता है कि यह फ़ॉन्ट‑वेट उदाहरण फ़ॉन्ट के वजन (मोटाई) का निरपेक्ष मान एक पूर्णांक संख्या के रूप में संग्रहीत करता है या नहीं। |
|
|  | [isRelative()](#isRelative--) | यह दर्शाता है कि यह font-weight इंस्टेंस फ़ॉन्ट के वजन (बोल्डनेस) का सापेक्ष मान संग्रहीत करता है या नहीं - पैरेंट एलिमेंट की बोल्डनेस की तुलना में। |
|
|  | [getValue()](#getValue--) | इस font-weight का मान स्ट्रिंग के रूप में लौटाता है। |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | निर्धारित करता है कि निर्दिष्ट FontWeight इंस्टेंस समान हैं या नहीं। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह FontWeight इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं। |
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश‑कोड लौटाता है। |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | जाँचता है कि दो \"FontWeight\" मान समान हैं या नहीं। |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | जाँचता है कि दो \"FontWeight\" मान असमान हैं या नहीं। |
|
|  | [fromNumber(int number)](#fromNumber-int-) | निर्दिष्ट संख्या से एक font-weight बनाता है। |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और सफलता पर एक वैध FontWeight इंस्टेंस लौटाता है। |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


पैरेंट तत्व से एक सापेक्ष फ़ॉन्ट वजन हल्का


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


पैरेंट तत्व से एक सापेक्ष फ़ॉन्ट वजन भारी


### Normal {#Normal}
```
public static final FontWeight Normal
```


सामान्य font weight। 400 के समान।


### Bold {#Bold}
```
public static final FontWeight Bold
```


बोल्ड font weight। 700 के समान।


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


सूचित करता है कि इस font-size का प्रारंभिक मान (Medium) है या नहीं


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


एक संख्या लौटाता है - 1 से 1000 के बीच पूर्णांक मान, जो फ़ॉन्ट की मोटाई का वर्णन करता है, या अपवाद फेंकता है, यदि वर्तमान मोटाई निरपेक्ष नहीं बल्कि सापेक्ष है।


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


यह दर्शाता है कि यह फ़ॉन्ट‑वेट उदाहरण फ़ॉन्ट के वजन (मोटाई) का निरपेक्ष मान एक पूर्णांक संख्या के रूप में संग्रहीत करता है या नहीं।


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


यह दर्शाता है कि यह font-weight इंस्टेंस फ़ॉन्ट के वजन (बोल्डनेस) का सापेक्ष मान संग्रहीत करता है या नहीं - पैरेंट एलिमेंट की बोल्डनेस की तुलना में।


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


इस font-weight का मान स्ट्रिंग के रूप में लौटाता है।


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


निर्धारित करता है कि निर्दिष्ट FontWeight इंस्टेंस समान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | समानता जाँचने के लिए अन्य FontWeight इंस्टेंस। |
|

**Returns:**
boolean - यदि समान हों तो true, यदि असमान हों तो false।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह FontWeight इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य अनकास्टेड FontWeight इंस्टेंस, null हो सकता है। |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


जाँचता है कि दो \"FontWeight\" मान समान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | जाँचने के लिए पहला मान |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


जाँचता है कि दो \"FontWeight\" मान असमान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | जाँचने के लिए पहला मान |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो false, अन्यथा true

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


निर्दिष्ट संख्या से एक font-weight बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | number | int | अहस्ताक्षरित पूर्णांक, [1..1000] सीमा के भीतर होना चाहिए। |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और सफलता पर एक वैध FontWeight इंस्टेंस लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | input | java.lang.String | पार्स करने के लिए इनपुट स्ट्रिंग। |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | सफलता पर वैध FontWeight मान या विफलता पर #Normal.Normal। |
|

**Returns:**
boolean - पार्सिंग की सफलता (true) या विफलता (false)।

