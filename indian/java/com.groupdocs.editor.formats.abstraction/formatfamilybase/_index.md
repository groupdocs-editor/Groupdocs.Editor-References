---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "फ़ॉर्मेट फ़ैमिलियों के लिए बेस क्लास को दर्शाता है, जो फ़ॉर्मेट फ़ैमिली इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

फ़ॉर्मेट परिवारों के लिए बेस क्लास को दर्शाता है, जो फ़ॉर्मेट फ़ैमिली इंस्टेंसेज़ के लिए सामान्य कार्यक्षमता प्रदान करता है।

<br />

*** ** * ** ***

यह क्लास एब्स्ट्रैक्ट है और इसे एक डेराइव्ड क्लास द्वारा इनहेरिट किया जाना चाहिए जो वास्तविक फ़ॉर्मेट फ़ैमिली विवरण निर्दिष्ट करती है।

<br />


## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getId()](#getId--) | फ़ॉर्मेट फ़ैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
|
|  | [getName()](#getName--) | फ़ॉर्मेट परिवार का नाम प्राप्त करता है। |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
|
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | निर्दिष्ट प्रकार के सभी इंस्टेंस प्राप्त करता है |
T
जो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) से व्युत्पन्न होते हैं।
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
|
|  | [hashCode()](#hashCode--) | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है। |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है। |
T
जिसका निर्दिष्ट पहचानकर्ता है।
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है। |
T
जिसका निर्दिष्ट नाम है।
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | निर्धारित करता है कि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस बराबर हैं या नहीं। |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | निर्धारित करता है कि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस असमान हैं या नहीं। |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | निर्धारित करता है कि एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस निर्दिष्ट स्ट्रिंग नाम के बराबर है या नहीं। |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | निर्धारित करता है कि एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस निर्दिष्ट स्ट्रिंग नाम के असमान है या नहीं। |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस को अप्रत्यक्ष रूप से पूर्णांक में परिवर्तित करता है। |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस को अप्रत्यक्ष रूप से स्ट्रिंग में परिवर्तित करता है। |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | फ़ॉर्मेट परिवार नाम का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है। |
|
|  | [fromId(int id)](#fromId-int-) | फ़ॉर्मेट परिवार आईडी का प्रतिनिधित्व करने वाले पूर्णांक को एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है। |
|
### getId() {#getId--}
```
public final int getId()
```


फ़ॉर्मेट फ़ैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


फ़ॉर्मेट परिवार का नाम प्राप्त करता है।


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | वर्तमान इंस्टेंस के साथ तुलना करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस। |
|

**Returns:**
boolean - true यदि निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) वर्तमान इंस्टेंस के बराबर है; अन्यथा, false।

### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।


**Returns:**
java.lang.String - एक स्ट्रिंग जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है, जो Name प्रॉपर्टी का मान है।

<br />

*** ** * ** ***

यह मेथड object.ToString को ओवरराइड करके ऑब्जेक्ट की Name प्रॉपर्टी लौटाता है।

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


निर्दिष्ट प्रकार के सभी इंस्टेंस प्राप्त करता है
T
जो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) से व्युत्पन्न होते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - निर्दिष्ट प्रकार T के इंस्टेंस की एक क्रमबद्ध संग्रह।


T
: फ़ॉर्मेट परिवार का प्रकार।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | वर्तमान इंस्टेंस के साथ तुलना करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस। |
|

**Returns:**
boolean - true यदि निर्दिष्ट [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) वर्तमान इंस्टेंस के बराबर है; अन्यथा, false।

### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है।


**Returns:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।

<br />

*** ** * ** ***

यह मेथड object.GetHashCode को ओवरराइड करता है। हैश कोड ऑब्जेक्ट की Id और Name प्रॉपर्टीज़ का उपयोग करके गणना किया जाता है। unchecked कॉन्टेक्स्ट ओवरफ़्लो की अनुमति देता है, जो हैश कोड गणना के संदर्भ में स्वीकार्य है।

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है।
T
जिसका निर्दिष्ट पहचानकर्ता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | मान | int | फ़ॉर्मेट परिवार का पहचानकर्ता। |


T
: फ़ॉर्मेट परिवार का प्रकार।
|

**Returns:**
T - निर्दिष्ट प्रकार T का एक इंस्टेंस, जिसमें निर्दिष्ट पहचानकर्ता है।

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है।
T
जिसका निर्दिष्ट नाम है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | नाम | java.lang.String | फ़ॉर्मेट परिवार का नाम। |


T
: फ़ॉर्मेट परिवार का प्रकार।
|

**Returns:**
T - निर्दिष्ट प्रकार T का एक उदाहरण, निर्दिष्ट नाम के साथ।

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


निर्धारित करता है कि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस बराबर हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | पहला [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) तुलना करने वाला उदाहरण। |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | दूसरा [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) तुलना करने वाला उदाहरण। |
|

**Returns:**
boolean - यदि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण समान हैं तो true; अन्यथा false।

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


निर्धारित करता है कि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस असमान हैं या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | पहला [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) तुलना करने वाला उदाहरण। |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | दूसरा [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) तुलना करने वाला उदाहरण। |
|

**Returns:**
boolean - यदि दो [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण समान नहीं हैं तो true; अन्यथा false।

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


निर्धारित करता है कि एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस निर्दिष्ट स्ट्रिंग नाम के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | तुलना करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण। |
|
|  | name | java.lang.String | तुलना करने के लिए स्ट्रिंग नाम, [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण के साथ। |
|

**Returns:**
boolean - यदि [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण का नाम निर्दिष्ट स्ट्रिंग नाम के बराबर है तो true; अन्यथा false।

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


निर्धारित करता है कि एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस निर्दिष्ट स्ट्रिंग नाम के असमान है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | तुलना करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण। |
|
|  | name | java.lang.String | तुलना करने के लिए स्ट्रिंग नाम, [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण के साथ। |
|

**Returns:**
boolean - यदि [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण का नाम निर्दिष्ट स्ट्रिंग नाम के बराबर नहीं है तो true; अन्यथा false।

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस को अप्रत्यक्ष रूप से पूर्णांक में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | परिवर्तित करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण। |
|

**Returns:**
int - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण का विशिष्ट पहचानकर्ता।

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस को अप्रत्यक्ष रूप से स्ट्रिंग में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | परिवर्तित करने के लिए [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण। |
|

**Returns:**
java.lang.String - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) उदाहरण का नाम।

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


फ़ॉर्मेट परिवार नाम का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | परिवार | java.lang.String | परिवर्तित करने के लिए फ़ॉर्मेट परिवार का नाम। |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


फ़ॉर्मेट परिवार आईडी का प्रतिनिधित्व करने वाले पूर्णांक को एक [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | id | int | परिवर्तित करने के लिए फ़ॉर्मेट परिवार का ID। |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

