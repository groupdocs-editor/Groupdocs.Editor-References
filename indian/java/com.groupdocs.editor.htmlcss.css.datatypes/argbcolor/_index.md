---
title: "ArgbColor"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "ARGB फ़ॉर्मेट में एक रंग मान को कनवर्टर्स और सीरियलाइज़र्स के साथ दर्शाता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

ARGB फ़ॉर्मेट में एक रंग मान को कनवर्टर्स और सीरियलाइज़र्स के साथ दर्शाता है।

<br />

*** ** * ** ***

यह प्रकार CSS संचालन (परंतु केवल इन्हीं तक सीमित नहीं) के लिए उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | निर्दिष्ट लाल, हरा, नीला और अल्फा चैनलों से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | निर्दिष्ट लाल, हरा, नीला चैनलों से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है, जबकि अल्फा चैनल पूरी तरह अपारदर्शी होता है |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | एकल मान से पूरी तरह अपारदर्शी (A=255) रंग बनाता है, जो सभी चैनलों पर लागू होगा |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | निर्दिष्ट [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है |
|
|  | [getValue()](#getValue--) | रंग का Int32 मान प्राप्त करता है। |
|
|  | [getA()](#getA--) | रंग का अल्फा भाग प्राप्त करता है। |
|
|  | [getAlpha()](#getAlpha--) | रंग का अल्फा भाग प्रतिशत में प्राप्त करता है (0..1)। |
|
|  | [getR()](#getR--) | रंग का लाल भाग प्राप्त करता है। |
|
|  | [getG()](#getG--) | रंग का हरा भाग प्राप्त करता है। |
|
|  | [getB()](#getB--) | रंग का नीला भाग प्राप्त करता है। |
|
|  | [isEmpty()](#isEmpty--) | अप्रारंभित रंग - सभी 4 चैनलों को 0 पर सेट किया गया है। |
|
|  | [isDefault()](#isDefault--) | निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण डिफ़ॉल्ट (पारदर्शी) है या नहीं - सभी 4 चैनलों को 0 पर सेट किया गया है |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पूरी तरह पारदर्शी है या नहीं - इसका अल्फा चैनल न्यूनतम (0) मान रखता है, इसलिए अन्य R, G, B चैनलों का कोई दृश्य प्रभाव नहीं रहता। |
|
|  | [isTranslucent()](#isTranslucent--) | निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पारदर्शी है (पूरी तरह पारदर्शी नहीं, लेकिन पूरी तरह अपारदर्शी भी नहीं) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पूरी तरह अपारदर्शी है, बिना पारदर्शिता के (इसका अल्फा चैनल अधिकतम मान रखता है) |
|
|  | [toSystemColor()](#toSystemColor--) | इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण का मान [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) उदाहरण में परिवर्तित करता है और उसे लौटाता है |
|
|  | [toRGBA()](#toRGBA--) | इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को 'rgba' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
|
|  | [toRGB()](#toRGB--) | इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को 'rgb' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
|
|  | [serializeDefault()](#serializeDefault--) | इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को पारदर्शिता के आधार पर सबसे उपयुक्त CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
|
|  | [toString()](#toString--) | इसी तरह जैसा #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं। |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते। |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | दो [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंगों की समानता जांचता है |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | दो [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंगों की समानता जांचता है |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | जाँचता है कि कोई अन्य वस्तु इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण के बराबर है या नहीं। |
|
|  | [hashCode()](#hashCode--) | वर्तमान रंग को परिभाषित करने वाला हैश कोड लौटाता है। |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


निर्दिष्ट लाल, हरा, नीला और अल्फा चैनलों से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | लाल | int | लाल चैनल मान |
|
|  | हरा | int | हरा चैनल मान |
|
|  | नीला | int | नीला चैनल मान |
|
|  | अल्फा | int | अल्फा चैनल मान |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


निर्दिष्ट लाल, हरा, नीला चैनलों से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है, जबकि अल्फा चैनल पूरी तरह अपारदर्शी होता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | लाल | int | लाल चैनल मान |
|
|  | हरा | int | हरा चैनल मान |
|
|  | नीला | int | नीला चैनल मान |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


एकल मान से पूरी तरह अपारदर्शी (A=255) रंग बनाता है, जो सभी चैनलों पर लागू होगा


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | बाइट | एक बाइट मान, जो लाल, हरा और नीला चैनलों के लिए समान है |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


निर्दिष्ट [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) से एक [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) मान बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रंग | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


रंग का Int32 मान प्राप्त करता है।


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


रंग का अल्फा भाग प्राप्त करता है।


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


रंग का अल्फा भाग प्रतिशत में प्राप्त करता है (0..1)।


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


रंग का लाल भाग प्राप्त करता है।


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


रंग का हरा भाग प्राप्त करता है।


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


रंग का नीला भाग प्राप्त करता है।


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


अप्रारंभित रंग - सभी 4 चैनलों को 0 पर सेट किया गया है। यह डिफ़ॉल्ट और ट्रांसपेरेंट के समान है।


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण डिफ़ॉल्ट (पारदर्शी) है या नहीं - सभी 4 चैनलों को 0 पर सेट किया गया है


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पूरी तरह पारदर्शी है या नहीं - इसका अल्फा चैनल न्यूनतम (0) मान रखता है, इसलिए अन्य R, G, B चैनलों का कोई दृश्य प्रभाव नहीं रहता।


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पारदर्शी है (पूरी तरह पारदर्शी नहीं, लेकिन पूरी तरह अपारदर्शी भी नहीं)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


निर्देशित करता है कि यह [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण पूरी तरह अपारदर्शी है, बिना पारदर्शिता के (इसका अल्फा चैनल अधिकतम मान रखता है)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण का मान [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) उदाहरण में परिवर्तित करता है और उसे लौटाता है


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को 'rgba' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' स्वरूप वाली स्ट्रिंग

### toRGB() {#toRGB--}
```
public final String toRGB()
```


इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को 'rgb' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है


**Returns:**
java.lang.String - 'rgb(r, g, b)' स्वरूप वाली स्ट्रिंग

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण को पारदर्शिता के आधार पर सबसे उपयुक्त CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' या 'rgb(r, g, b)' स्वरूप वाली स्ट्रिंग

### toString() {#toString--}
```
public String toString()
```


इसी तरह जैसा #serializeDefault.serializeDefault


**Returns:**
java.lang.String - #serializeDefault.serializeDefault में समान रिटर्न वैल्यू

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | उपयोग करने के लिए पहला रंग। |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | उपयोग करने के लिए दूसरा रंग। |
|

**Returns:**
boolean - यदि दोनों रंग समान हैं तो True, अन्यथा false.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | उपयोग करने के लिए पहला रंग। |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | उपयोग करने के लिए दूसरा रंग। |
|

**Returns:**
boolean - यदि दोनों रंग समान नहीं हैं तो True, अन्यथा false.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


दो [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंगों की समानता जांचता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | अन्य [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंग |
|

**Returns:**
boolean - यदि दोनों रंग समान हैं तो True, अन्यथा false.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


दो [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंगों की समानता जांचता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | अन्य [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) रंग, ICssDataType में कास्ट किया गया |
|

**Returns:**
boolean - यदि दोनों रंग समान हैं तो True, अन्यथा false.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


जाँचता है कि कोई अन्य वस्तु इस [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) उदाहरण के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | अन्य | java.lang.Object | परीक्षण के लिए वस्तु। |
|

**Returns:**
boolean - यदि दो वस्तुएँ समान हैं तो True, अन्यथा false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान रंग को परिभाषित करने वाला हैश कोड लौटाता है।


**Returns:**
int - हैशकोड का पूर्णांक मान।

