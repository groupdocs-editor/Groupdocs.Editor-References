---
title: "लंबाई"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी समर्थित इकाई में CSS लंबाई मान का प्रतिनिधित्व करता है, जिसमें प्रतिशत और बिना इकाई वाला प्रकार शामिल है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

किसी भी समर्थित इकाई में CSS लंबाई मान का प्रतिनिधित्व करता है, जिसमें प्रतिशत शामिल है
और बिना इकाई वाला प्रकार। मान पूर्णांक या फ्लोट हो सकते हैं, नकारात्मक, शून्य और
सकारात्मक। अपरिवर्तनीय संरचना।

*** ** * ** ***


यह प्रकार अगले CSS डेटा प्रकारों को कवर करता है:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Length()](#Length--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | बिना इकाई वाला पूर्णांक शून्य - डिफ़ॉल्ट मान, डिफ़ॉल्ट पैरामीटरलेस के समान |
कंस्ट्रक्टर
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | निर्दिष्ट फ्लोट संख्या द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है |
और इकाई
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | निर्दिष्ट डबल संख्या द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है |
और इकाई
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | निर्दिष्ट पूर्णांक द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है |
संख्या और इकाई
|
|  | [isUnitlessZero()](#isUnitlessZero--) | निर्धारित करता है कि यह इंस्टेंस बिना इकाई वाला शून्य है या नहीं। |
|
|  | [isDefault()](#isDefault--) | संकेत करता है कि इस Length इंस्टेंस का डिफ़ॉल्ट मान \u2014 बिना इकाई है |
शून्य।
|
|  | [getUnitType()](#getUnitType--) | इस Length इंस्टेंस का इकाई प्रकार लौटाता है। |
|
|  | [isInteger()](#isInteger--) | संकेत करता है कि इस Length इंस्टेंस का संख्यात्मक मान था |
मूल रूप से एक पूर्णांक (INT32) संख्या के रूप में निर्दिष्ट और संग्रहीत किया गया
|
|  | [isFloat()](#isFloat--) | संकेत करता है कि इस Length इंस्टेंस का संख्यात्मक मान था |
मूल रूप से एक फ्लोट (FP32) संख्या के रूप में निर्दिष्ट और संग्रहीत किया गया
|
|  | [getFloatValue()](#getFloatValue--) | Length इंस्टेंस का फ्लोट संख्यात्मक मान लौटाता है। |
|
|  | [getIntegerValue()](#getIntegerValue--) | यदि यह है, तो इस Length इंस्टेंस का पूर्णांक संख्यात्मक मान लौटाता है, |
आंतरिक रूप से एक पूर्णांक के रूप में संग्रहीत है, या यदि यह था तो एक अपवाद फेंकता है,
मूल रूप से एक फ्लोट संख्या के रूप में संग्रहीत था।
|
|  | [isAbsolute()](#isAbsolute--) | जाँचता है कि लंबाई निरपेक्ष इकाइयों में दी गई है या नहीं। |
|
|  | [isRelative()](#isRelative--) | जाँचता है कि लंबाई सापेक्ष इकाइयों में दी गई है या नहीं। |
|
|  | [isZero()](#isZero--) | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान शून्य संख्या है या नहीं |
|
|  | [isNegative()](#isNegative--) | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान नकारात्मक संख्या है या नहीं |
|
|  | [isPositive()](#isPositive--) | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान सकारात्मक संख्या है या नहीं |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | मान का यूनिटलेस प्रकार है, लेकिन यह शून्य नहीं है - यह सकारात्मक या नकारात्मक है |
number
|
|  | [toPixel()](#toPixel--) | यदि संभव हो तो लंबाई को पिक्सेल की संख्या में परिवर्तित करता है। |
|
|  | [to(int unit)](#to-int-) | यदि संभव हो तो लंबाई को दिए गए इकाई में परिवर्तित करता है। |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | निर्दिष्ट इकाई प्रकार में इस लंबाई का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
|
|  | [serializeDefault()](#serializeDefault--) | इस लंबाई का मूल मूल स्वरूप में स्ट्रिंग प्रतिनिधित्व लौटाता है |
रूप (जैसे यह संग्रहीत है), बिना लंबाई मान को किसी अन्य में परिवर्तित किए
इकाई प्रकार
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | परिभाषित करता है कि यह मान अन्य निर्दिष्ट लंबाई के बराबर है या नहीं |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह लंबाई निर्दिष्ट वस्तु के बराबर है या नहीं |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | दिए गए फैक्टर पर दी गई लंबाई को गुणा करता है |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | दो दी गई लंबाइयों की समानता जाँचता है। |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | दो दी गई लंबाइयों की असमानता जाँचता है। |
|
|  | [hashCode()](#hashCode--) | इस Length इंस्टेंस का हैश-कोड गणना करता है और संयोजन द्वारा लौटाता है |
मान और इकाई प्रकार के हैश-कोड
|
|  | [deepClone()](#deepClone--) | इस Length इंस्टेंस की पूरी कॉपी लौटाता है |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | निर्दिष्ट इकाई नाम को पार्स करने का प्रयास करता है और एक का संबंधित मान लौटाता है |
इकाई enum।
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करने का प्रयास करता है, जिसमें इसका |
संख्यात्मक मान और इकाई नाम
|
|  | [parse(String input)](#parse-java.lang.String-) | निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करता है और लौटाता है, जिसमें इसका |
संख्यात्मक मान और इकाई नाम, या विफलता पर एक अपवाद फेंकता है
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


बिना इकाई वाला पूर्णांक शून्य - डिफ़ॉल्ट मान, डिफ़ॉल्ट पैरामीटरलेस के समान
कंस्ट्रक्टर


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


निर्दिष्ट फ्लोट संख्या द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है
और इकाई


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | float | \>कोई भी फ़्लोट (FP32) संख्या |
|
|  | इकाई | int | कोई भी मान्य इकाई प्रकार |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


निर्दिष्ट डबल संख्या द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है
और इकाई


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | double | कोई भी डबल (FP64) संख्या, जिसे फ़्लोट (FP32) में परिवर्तित किया जाएगा |
|
|  | इकाई | int | कोई भी मान्य इकाई प्रकार |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


निर्दिष्ट पूर्णांक द्वारा Length प्रकार का एक इंस्टेंस बनाता है और लौटाता है
संख्या और इकाई


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | int | कोई भी पूर्णांक संख्या |
|
|  | इकाई | int | कोई भी मान्य इकाई प्रकार |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


निर्धारित करता है कि यह उदाहरण इकाई‑रहित शून्य है या नहीं। इकाई‑रहित शून्य
इस प्रकार का डिफ़ॉल्ट मान है। यह IsDefault प्रॉपर्टी के समान है।


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


संकेत करता है कि इस Length इंस्टेंस का डिफ़ॉल्ट मान \u2014 बिना इकाई है
शून्य। यह IsUnitlessZero प्रॉपर्टी के समान है।


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


इस Length इंस्टेंस का इकाई प्रकार लौटाता है।


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


संकेत करता है कि इस Length इंस्टेंस का संख्यात्मक मान था
मूल रूप से एक पूर्णांक (INT32) संख्या के रूप में निर्दिष्ट और संग्रहीत किया गया


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


संकेत करता है कि इस Length इंस्टेंस का संख्यात्मक मान था
मूल रूप से एक फ्लोट (FP32) संख्या के रूप में निर्दिष्ट और संग्रहीत किया गया


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Length उदाहरण का फ़्लोट संख्यात्मक मान लौटाता है। कभी भी एक
अपवाद - यदि आवश्यक हो तो Integer मान को Float में परिवर्तित करता है।


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


यदि यह है, तो इस Length इंस्टेंस का पूर्णांक संख्यात्मक मान लौटाता है,
आंतरिक रूप से एक पूर्णांक के रूप में संग्रहीत है, या यदि यह था तो एक अपवाद फेंकता है,
मूल रूप से एक फ्लोट संख्या के रूप में संग्रहीत था।


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


जाँचता है कि लंबाई निरपेक्ष इकाइयों में दी गई है या नहीं। ऐसी लंबाई हो सकती है
पिक्सेल में परिवर्तित।


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


जाँचता है कि लंबाई सापेक्ष इकाइयों में दी गई है या नहीं। ऐसी लंबाई नहीं हो सकती
पिक्सेल में परिवर्तित।


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


निर्धारित करता है कि इस लंबाई का संख्यात्मक मान शून्य संख्या है या नहीं


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


निर्धारित करता है कि इस लंबाई का संख्यात्मक मान नकारात्मक संख्या है या नहीं


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


निर्धारित करता है कि इस लंबाई का संख्यात्मक मान सकारात्मक संख्या है या नहीं


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


मान का यूनिटलेस प्रकार है, लेकिन यह शून्य नहीं है - यह सकारात्मक या नकारात्मक है
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


यदि संभव हो तो लंबाई को पिक्सेल की संख्या में परिवर्तित करता है। यदि वर्तमान
इकाई सापेक्ष है, तो एक अपवाद फेंका जाएगा।


**Returns:**
float - वर्तमान लंबाई द्वारा प्रतिनिधित्व किए गए पिक्सेल की संख्या।

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


यदि संभव हो तो लंबाई को दिए गए इकाई में परिवर्तित करता है। यदि वर्तमान या
दिए गई इकाई सापेक्ष है, तो एक अपवाद फेंका जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | इकाई | int | जिस इकाई में परिवर्तित करना है। |
|

**Returns:**
float - वर्तमान लंबाई की दी गई इकाई में मान।

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


निर्दिष्ट इकाई प्रकार में इस लंबाई का स्ट्रिंग प्रतिनिधित्व लौटाता है।
संख्यात्मक मान को इकाई प्रकार परिवर्तन के अनुसार परिवर्तित किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | इकाई | int | निर्दिष्ट इकाई, जिसमें इस उदाहरण को स्ट्रिंग में सीरियलाइज़ करने से पहले परिवर्तित किया जाना चाहिए। यह मान्य होना चाहिए। इकाई‑रहित नहीं हो सकता। |
|

**Returns:**
java.lang.String - स्ट्रिंग प्रतिनिधित्व

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


इस लंबाई का मूल मूल स्वरूप में स्ट्रिंग प्रतिनिधित्व लौटाता है
रूप (जैसे यह संग्रहीत है), बिना लंबाई मान को किसी अन्य में परिवर्तित किए
इकाई प्रकार


**Returns:**
java.lang.String - स्ट्रिंग उदाहरण

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


परिभाषित करता है कि यह मान अन्य निर्दिष्ट लंबाई के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length प्रकार का अन्य उदाहरण |
|

**Returns:**
boolean - यदि समान हो तो true, अन्यथा false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह लंबाई निर्दिष्ट वस्तु के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | Length प्रकार का अन्य उदाहरण, जो System.Object या किसी अन्य अमूर्त प्रकार या इंटरफ़ेस में बॉक्स किया गया है |
|

**Returns:**
boolean - यदि समान हो तो true, अन्यथा false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


दिए गए फैक्टर पर दी गई लंबाई को गुणा करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - गुणांक |
|
|  | गुणक | int | मनमाना पूर्णांक - गुणक |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


दो दी गई लंबाइयों की समानता जाँचता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | बाएँ लंबाई ऑपरेण्ड। |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | दाएँ लंबाई ऑपरेण्ड। |
|

**Returns:**
boolean - यदि दोनों लंबाइयाँ समान हों तो True, अन्यथा false।

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


दो दी गई लंबाइयों की असमानता जाँचता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | बाएँ लंबाई ऑपरेण्ड। |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | दाएँ लंबाई ऑपरेण्ड। |
|

**Returns:**
boolean - यदि दोनों लंबाइयाँ समान न हों तो True, अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस Length इंस्टेंस का हैश-कोड गणना करता है और संयोजन द्वारा लौटाता है
मान और इकाई प्रकार के हैश-कोड


**Returns:**
int - पूर्णांक संख्या

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


इस Length इंस्टेंस की पूरी कॉपी लौटाता है


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


निर्दिष्ट इकाई नाम को पार्स करने का प्रयास करता है और एक का संबंधित मान लौटाता है
Unit enum. यदि उपयुक्त LengthUnit नहीं मिलता है तो LengthUnit.Unitless लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | unitName | java.lang.String | String, जो इकाई का नाम दर्शाता है |
|

**Returns:**
int - किसी भी स्थिति में Unit enum का मान, जब उपयुक्त इकाई नहीं मिलती तो LengthUnit.Unitless

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करने का प्रयास करता है, जिसमें इसका
संख्यात्मक मान और इकाई नाम


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | input | java.lang.String | इनपुट स्ट्रिंग, जिसे पार्स किया जाना चाहिए |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | आउटपुट पैरामीटर, जिसमें पार्सिंग का परिणाम होता है। यदि पार्सिंग असफल हो, तो इसमें डिफ़ॉल्ट Length मान \\u2014 एक इकाई‑रहित शून्य शामिल होता है। |
|

**Returns:**
boolean - यदि पार्सिंग सफल हो तो True, असफल होने पर false

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करता है और लौटाता है, जिसमें इसका
संख्यात्मक मान और इकाई नाम, या विफलता पर एक अपवाद फेंकता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | input | java.lang.String | इनपुट स्ट्रिंग, जिसे पार्स किया जाना चाहिए |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

