---
title: "InvalidFormField"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "FormFieldManager.FixInvalidFormFieldNames ऑपरेशन के दौरान अमान्य फ़ॉर्म फ़ील्ड नामों के अद्यतन को दर्शाता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

अमान्य फ़ॉर्म फ़ील्ड नामों के अद्यतन का प्रतिनिधित्व करता है के दौरान
FormFieldManager.FixInvalidFormFieldNames
ऑपरेशन।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | निर्दिष्ट नाम के साथ [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | फ़ॉर्म फ़ील्ड का मूल नाम प्राप्त करता है जिसे बाहर से संशोधित नहीं किया जा सकता। |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | मरम्मत के बाद फ़ॉर्म फ़ील्ड के लिए नया नाम प्राप्त करता है या सेट करता है। |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | मरम्मत के बाद फ़ॉर्म फ़ील्ड के लिए नया नाम प्राप्त करता है या सेट करता है। |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


निर्दिष्ट नाम के साथ [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड का मूल नाम। |
|

### getName() {#getName--}
```
public final String getName()
```


फ़ॉर्म फ़ील्ड का मूल नाम प्राप्त करता है जिसे बाहर से संशोधित नहीं किया जा सकता।
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


मरम्मत के बाद फ़ॉर्म फ़ील्ड के लिए नया नाम प्राप्त करता है या सेट करता है।
यह नाम अन्य फ़ॉर्म फ़ील्ड के साथ डुप्लिकेट यूनिक आइडेंटिफ़ायर को हटाता है और एक यूनिक बुकमार्क नाम सेट करता है।

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


मरम्मत के बाद फ़ॉर्म फ़ील्ड के लिए नया नाम प्राप्त करता है या सेट करता है।
यह नाम अन्य फ़ॉर्म फ़ील्ड के साथ डुप्लिकेट यूनिक आइडेंटिफ़ायर को हटाता है और एक यूनिक बुकमार्क नाम सेट करता है।

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

