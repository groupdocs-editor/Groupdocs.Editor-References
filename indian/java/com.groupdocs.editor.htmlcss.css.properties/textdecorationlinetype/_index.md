---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "टेक्स्ट डेकोरेशन लाइन के प्रकारों जैसे underline, underscore, overline और line-through (strikethrough) को दर्शाता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

टेक्स्ट डेकोरेशन लाइन के प्रकारों को दर्शाता है: अंडरलाइन (अंडरस्कोर), ओवरलाइन, और लाइन‑थ्रू (स्ट्राइकथ्रू)।

<br />

*** ** * ** ***

अपरिवर्तनीय struct। https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line के समान।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [None](#None) | कोई टेक्स्ट डेकोरेशन उत्पन्न नहीं करता। |
|
|  | [Underline](#Underline) | पाठ की प्रत्येक पंक्ति के नीचे रेखा खींची जाती है। |
|
|  | [Overline](#Overline) | प्रत्येक टेक्स्ट की लाइन के ऊपर एक लाइन होती है। |
|
|  | [LineThrough](#LineThrough) | प्रत्येक टेक्स्ट की लाइन के मध्य में एक लाइन होती है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indicates whether this instance has an initial value \\\\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | यह दर्शाता है कि अंडरलाइन (अंडरस्कोर) सक्षम है या नहीं |
|
|  | [isOverline()](#isOverline--) | यह दर्शाता है कि ओवरलाइन सक्षम है या नहीं |
|
|  | [isLineThrough()](#isLineThrough--) | यह दर्शाता है कि स्ट्राइकथ्रू (लाइन-थ्रू) सक्षम है या नहीं |
|
|  | [getValue()](#getValue--) | इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है |
|
|  | [toString()](#toString--) | इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | यह दर्शाता है कि यह [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस निर्दिष्ट के बराबर है या नहीं |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | यह दर्शाता है कि यह [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस अनकास्टेड निर्दिष्ट के बराबर है या नहीं |
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस का हैश-कोड लौटाता है |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Checks whether two \"TextDecorationLineType\" values are equal |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Checks whether two \"TextDecorationLineType\" values are not equal |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | निर्दिष्ट पैरामीटरों द्वारा परिभाषित फ़्लैग्स के साथ एक [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस बनाता और लौटाता है |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और एक वैध [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस लौटाता है |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | दो निर्दिष्ट लाइन प्रकारों को मिलाता (जोड़ता) है और नया परिणामी लाइन प्रकार बनाता है, जहाँ फ़्लैग्स मिलाए जाते हैं (संघ) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | दूसरे निर्दिष्ट लाइन प्रकार को पहले निर्दिष्ट लाइन प्रकार से घटाता है और नया परिणामी लाइन प्रकार बनाता है, जहाँ केवल पहले ऑपरेण्ड के वे फ़्लैग्स होते हैं जो दूसरे ऑपरेण्ड में नहीं मिलते (अंतर) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | पहले और दूसरे लाइन प्रकारों के बीच इंटरसेक्शन लौटाता है, जहाँ केवल वही फ़्लैग्स सक्षम होते हैं जो दोनों ऑपरेण्ड में एक साथ सक्षम हैं। |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | विशिष्ट बाइट (8-बिट ऑक्टेट) को संबंधित [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) में कास्ट करता है, यदि कास्टिंग अमान्य है तो अपवाद फेंकता है |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


कोई टेक्स्ट डेकोरेशन उत्पन्न नहीं करता। प्रारंभिक मान।


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


पाठ की प्रत्येक पंक्ति के नीचे रेखा खींची जाती है।


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


प्रत्येक टेक्स्ट की लाइन के ऊपर एक लाइन होती है।


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


प्रत्येक टेक्स्ट की लाइन के मध्य में एक लाइन होती है।


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indicates whether this instance has an initial value \\\\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


यह दर्शाता है कि अंडरलाइन (अंडरस्कोर) सक्षम है या नहीं


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


यह दर्शाता है कि ओवरलाइन सक्षम है या नहीं


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


यह दर्शाता है कि स्ट्राइकथ्रू (लाइन-थ्रू) सक्षम है या नहीं


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


यह दर्शाता है कि यह [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस निर्दिष्ट के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | अन्य [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस |
|

**Returns:**
बूलियन -  true  यदि बराबर हों,  false  अन्यथा

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


यह दर्शाता है कि यह [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस अनकास्टेड निर्दिष्ट के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | java.lang.Object | अन्य [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस, ऑब्जेक्ट में कास्ट किया गया |
|

**Returns:**
बूलियन -  true  यदि बराबर हों,  false  अन्यथा

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस का हैश-कोड लौटाता है


**Returns:**
int - साइन्ड इंटीजर हैश-कोड

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Checks whether two \"TextDecorationLineType\" values are equal


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | जाँचने के लिए पहला ऑपरेण्ड |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | जाँच के लिए दूसरा ऑपरेण्ड |
|

**Returns:**
बूलियन -  true  यदि बराबर हों,  false  अन्यथा

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Checks whether two \"TextDecorationLineType\" values are not equal


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | जाँचने के लिए पहला ऑपरेण्ड |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | जाँच के लिए दूसरा ऑपरेण्ड |
|

**Returns:**
बूलियन -  यदि असमान हों तो true, अन्यथा false

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


निर्दिष्ट पैरामीटरों द्वारा परिभाषित फ़्लैग्स के साथ एक [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस बनाता और लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | isUnderline | boolean | निर्धारित करता है कि अंडरलाइन फ़्लैग सक्षम है या नहीं |
|
|  | isOverline | boolean | निर्धारित करता है कि ओवरलाइन फ़्लैग सक्षम है या नहीं |
|
|  | isLineThrough | boolean | निर्धारित करता है कि लाइन-थ्रू फ़्लैग सक्षम है या नहीं |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और एक वैध [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) इंस्टेंस लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | input | java.lang.String | इनपुट स्ट्रिंग |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | परिणाम। यदि पार्सिंग अमान्य है, तो यह #None.None मान होता है |
|

**Returns:**
बूलियन -  यदि पार्सिंग सफल हो तो true, विफलता पर false

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


दो निर्दिष्ट लाइन प्रकारों को मिलाता (जोड़ता) है और नया परिणामी लाइन प्रकार बनाता है, जहाँ फ़्लैग्स मिलाए जाते हैं (संघ)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | पहला लाइन प्रकार ऑपरेण्ड |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | दूसरा लाइन प्रकार ऑपरेण्ड |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


दूसरे निर्दिष्ट लाइन प्रकार को पहले निर्दिष्ट लाइन प्रकार से घटाता है और नया परिणामी लाइन प्रकार बनाता है, जहाँ केवल पहले ऑपरेण्ड के वे फ़्लैग्स होते हैं जो दूसरे ऑपरेण्ड में नहीं मिलते (अंतर)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | पहला लाइन प्रकार ऑपरेण्ड |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | दूसरा लाइन प्रकार ऑपरेण्ड |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


पहले और दूसरे लाइन प्रकारों के बीच इंटरसेक्शन लौटाता है, जहाँ केवल वही फ़्लैग सक्षम होते हैं जो दोनों ऑपरेण्ड में एक साथ सक्षम होते हैं। सभी ऑपरेटरों में इसका सबसे उच्च प्राथमिकता है (यूनियन और डिफरेंस से अधिक)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | पहला लाइन प्रकार ऑपरेण्ड |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | दूसरा लाइन प्रकार ऑपरेण्ड |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


विशिष्ट बाइट (8-बिट ऑक्टेट) को संबंधित [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) में कास्ट करता है, यदि कास्टिंग अमान्य है तो अपवाद फेंकता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | ऑक्टेट | बाइट | एक 8-बिट ऑक्टेट (बिटफ़ील्ड), जहाँ पहले 5 बिट शून्य होते हैं, जबकि अंतिम 3 फ़्लैग दर्शाते हैं |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
