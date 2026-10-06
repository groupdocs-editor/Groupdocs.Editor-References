---
title: "Ratio"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक ratio CSS डेटा प्रकार का प्रतिनिधित्व करता है जिसका उपयोग मीडिया क्वेरीज़ में पहलू अनुपातों का वर्णन करने और रास्टर छवियों के लिए दो बिना इकाई वाले मानों, जिन्हें numerator और denominator कहा जाता है, के बीच अनुपात दर्शाने के लिए किया जाता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

एक "ratio" CSS डेटा प्रकार का प्रतिनिधित्व करता है, जिसका उपयोग पहलू का वर्णन करने के लिए किया जाता है
मीडिया क्वेरीज़ में अनुपात और रास्टर छवियों के लिए अनुपात दर्शाकर
दो बिना इकाई वाले मानों, जिन्हें "numerator" और "denominator" कहा जाता है, के बीच। अपरिवर्तनीय
struct।


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [Single](#Single) | एकल डिफ़ॉल्ट ratio 1/1 |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | इस ratio का numerator लौटाता है |
|
|  | [getDenominator()](#getDenominator--) | इस ratio का denominator लौटाता है |
|
|  | [calculate()](#calculate--) | इस ratio की गणना करता है और इसे एकल फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है |
|
|  | [getInverseRatio()](#getInverseRatio--) | इस ratio के लिए एक inverse (reciprocal) ratio उत्पन्न करता है और लौटाता है |
|
|  | [serializeDefault()](#serializeDefault--) | इस ratio को स्ट्रिंग में सीरियलाइज़ करता है और लौटाता है |
|
|  | [toString()](#toString--) | इस ratio का स्ट्रिंग प्रतिनिधित्व लौटाता है; जैसा कि |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | निर्धारित करता है कि यह ratio डिफ़ॉल्ट मान रखता है या "1/1" (एकल) है |
|
|  | [deepClone()](#deepClone--) | इस ratio की पूरी कॉपी लौटाता है |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | निर्धारित करता है कि यह instance निर्दिष्ट "Ratio" instance के बराबर है या नहीं |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, |
जो संभवतः एक अन्य "Ratio" instance है
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | दो अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं। |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | दो अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते। |
मेल।
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे इसके |
जीवनकाल
|
|  | [create(int numerator, int denominator)](#create-int-int-) | निर्दिष्ट अंशांक और से एक Ratio इंस्टेंस बनाता और लौटाता है |
हर
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


एकल डिफ़ॉल्ट ratio 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


इस ratio का numerator लौटाता है


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


इस ratio का denominator लौटाता है


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


इस ratio की गणना करता है और इसे एकल फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है


**Returns:**
double - डबल प्रिसीजन वाला फ्लोटिंग-पॉइंट संख्या

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


इस ratio के लिए एक inverse (reciprocal) ratio उत्पन्न करता है और लौटाता है


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


इस ratio को स्ट्रिंग में सीरियलाइज़ करता है और लौटाता है


**Returns:**
java.lang.String - "अंशांक/हर" प्रारूप में स्ट्रिंग

### toString() {#toString--}
```
public String toString()
```


इस ratio का स्ट्रिंग प्रतिनिधित्व लौटाता है; जैसा कि
"SerializeDefault()"


**Returns:**
java.lang.String - "अंशांक/हर" प्रारूप में स्ट्रिंग

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


निर्धारित करता है कि यह ratio डिफ़ॉल्ट मान रखता है या "1/1" (एकल) है


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


इस ratio की पूरी कॉपी लौटाता है


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


निर्धारित करता है कि यह instance निर्दिष्ट "Ratio" instance के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | इसके साथ समानता जांचने के लिए अन्य Ratio इंस्टेंस |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं,
जो संभवतः एक अन्य "Ratio" instance है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | अन्य | java.lang.Object | इसके साथ समानता जांचने के लिए अन्य System.Object इंस्टेंस, जो संभवतः Ratio प्रकार का है |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


दो अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | उपयोग करने के लिए पहला अनुपात। |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | उपयोग करने के लिए दूसरा अनुपात। |
|

**Returns:**
boolean - यदि दोनों अनुपात समान हों तो true, अन्यथा false।

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


दो अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते।
मेल।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | उपयोग करने के लिए पहला अनुपात। |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | उपयोग करने के लिए दूसरा अनुपात। |
|

**Returns:**
boolean - यदि दोनों अनुपात समान न हों तो true, अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे इसके
जीवनकाल


**Returns:**
int - साइन किया हुआ 4-बाइट पूर्णांक, जो इस इंस्टेंस के लिए अपरिवर्तनीय है

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


निर्दिष्ट अंशांक और से एक Ratio इंस्टेंस बनाता और लौटाता है
हर


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | अंशांक | int | अनुपात के लिए अंशांक। यह एक सख्ती से सकारात्मक पूर्णांक होना चाहिए। |
|
|  | हर | int | अनुपात के लिए हर। यह एक सख्ती से सकारात्मक पूर्णांक होना चाहिए। |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

