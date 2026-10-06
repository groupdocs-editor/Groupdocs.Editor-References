---
title: "CheckBoxForm"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक फ़ॉर्म फ़ील्ड का प्रतिनिधित्व करता है जो चेकबॉक्स दिखाता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.words.fieldmanagement/checkboxform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CheckBoxForm implements IFormField
```

एक फ़ॉर्म फ़ील्ड का प्रतिनिधित्व करता है जो चेकबॉक्स दिखाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CheckBoxForm(String stylesheet, String name)](#CheckBoxForm-java.lang.String-java.lang.String-) | निर्दिष्ट स्टाइलशीट और नाम के साथ [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | फ़ॉर्म फ़ील्ड पर लागू stylesheet प्राप्त करता है। |
|
|  | [getReadonly()](#getReadonly--) | फ़ॉर्म फ़ील्ड केवल‑पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | फ़ॉर्म फ़ील्ड केवल‑पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
|
|  | [getName()](#getName--) | फ़ॉर्म फ़ील्ड का नाम प्राप्त करता है। |
|
|  | [getType()](#getType--) | फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है, जो इस क्लास के लिए हमेशा FormFieldType.CheckBox होता है। |
|
|  | [getLocaleId()](#getLocaleId--) | फ़ॉर्म फ़ील्ड का locale ID प्राप्त या सेट करता है, जो फ़ॉर्म फ़ील्ड से जुड़ी संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है। |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | फ़ॉर्म फ़ील्ड का locale ID प्राप्त या सेट करता है, जो फ़ॉर्म फ़ील्ड से जुड़ी संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है। |
|
|  | [getStatusText()](#getStatusText--) | फ़ॉर्म फ़ील्ड से जुड़ा स्टेटस टेक्स्ट प्राप्त करता है या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर स्टेटस बार में प्रदर्शित होता है। |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | फ़ॉर्म फ़ील्ड से जुड़ा स्टेटस टेक्स्ट प्राप्त करता है या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर स्टेटस बार में प्रदर्शित होता है। |
|
|  | [getHelpText()](#getHelpText--) | फ़ॉर्म फ़ील्ड से जुड़ा help टेक्स्ट प्राप्त या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर और उपयोगकर्ता F1 दबाने पर संदेश बॉक्स में प्रदर्शित होता है। |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | फ़ॉर्म फ़ील्ड से जुड़ा help टेक्स्ट प्राप्त या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर और उपयोगकर्ता F1 दबाने पर संदेश बॉक्स में प्रदर्शित होता है। |
|
|  | [getValue()](#getValue--) | फ़ॉर्म फ़ील्ड का मान प्राप्त करता है या सेट करता है, जो चेकबॉक्स की स्थिति को दर्शाता है। |
|
|  | [setValue(boolean value)](#setValue-boolean-) | फ़ॉर्म फ़ील्ड का मान प्राप्त करता है या सेट करता है, जो चेकबॉक्स की स्थिति को दर्शाता है। |
|
### CheckBoxForm(String stylesheet, String name) {#CheckBoxForm-java.lang.String-java.lang.String-}
```
public CheckBoxForm(String stylesheet, String name)
```


निर्दिष्ट स्टाइलशीट और नाम के साथ [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | stylesheet | java.lang.String | फ़ॉर्म फ़ील्ड पर लागू करने के लिए stylesheet। |
|
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड का नाम। |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


फ़ॉर्म फ़ील्ड पर लागू stylesheet प्राप्त करता है।


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


फ़ॉर्म फ़ील्ड केवल‑पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


फ़ॉर्म फ़ील्ड केवल‑पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


फ़ॉर्म फ़ील्ड का नाम प्राप्त करता है।


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है, जो इस क्लास के लिए हमेशा FormFieldType.CheckBox होता है।


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


फ़ॉर्म फ़ील्ड का locale ID प्राप्त या सेट करता है, जो फ़ॉर्म फ़ील्ड से जुड़ी संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है।

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId प्रॉपर्टी एक लोकेल पहचानकर्ता (LCID) निर्दिष्ट करती है जो किसी विशिष्ट संस्कृति या क्षेत्र से संबंधित होता है।

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


फ़ॉर्म फ़ील्ड का locale ID प्राप्त या सेट करता है, जो फ़ॉर्म फ़ील्ड से जुड़ी संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है।

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId प्रॉपर्टी एक लोकेल पहचानकर्ता (LCID) निर्दिष्ट करती है जो किसी विशिष्ट संस्कृति या क्षेत्र से संबंधित होता है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


फ़ॉर्म फ़ील्ड से जुड़ा स्टेटस टेक्स्ट प्राप्त करता है या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर स्टेटस बार में प्रदर्शित होता है।

<br />

*** ** * ** ***

यदि इसे false पर सेट किया जाता है, तो स्थिति पाठ लागू नहीं होगा।

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


फ़ॉर्म फ़ील्ड से जुड़ा स्टेटस टेक्स्ट प्राप्त करता है या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर स्टेटस बार में प्रदर्शित होता है।

<br />

*** ** * ** ***

यदि इसे false पर सेट किया जाता है, तो स्थिति पाठ लागू नहीं होगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


फ़ॉर्म फ़ील्ड से जुड़ा help टेक्स्ट प्राप्त या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर और उपयोगकर्ता F1 दबाने पर संदेश बॉक्स में प्रदर्शित होता है।

<br />

*** ** * ** ***

यदि इसे false पर सेट किया जाता है, तो सहायता पाठ लागू नहीं होगा।

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


फ़ॉर्म फ़ील्ड से जुड़ा help टेक्स्ट प्राप्त या सेट करता है, वह स्रोत जो फ़ॉर्म फ़ील्ड के फोकस में होने पर और उपयोगकर्ता F1 दबाने पर संदेश बॉक्स में प्रदर्शित होता है।

<br />

*** ** * ** ***

यदि इसे false पर सेट किया जाता है, तो सहायता पाठ लागू नहीं होगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final boolean getValue()
```


फ़ॉर्म फ़ील्ड का मान प्राप्त करता है या सेट करता है, जो चेकबॉक्स की स्थिति को दर्शाता है।


**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


फ़ॉर्म फ़ील्ड का मान प्राप्त करता है या सेट करता है, जो चेकबॉक्स की स्थिति को दर्शाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

