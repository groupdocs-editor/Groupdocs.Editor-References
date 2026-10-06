---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "फ़ॉर्म फ़ील्ड्स का एक संग्रह दर्शाता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

फ़ॉर्म फ़ील्ड्स का एक संग्रह दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | नया उदाहरण प्रारंभ करता है [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) क्लास का। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | संग्रह में एक फ़ॉर्म फ़ील्ड सम्मिलित करता है। |
|
|  | [get(String name)](#get-java.lang.String-) | निर्दिष्ट नाम वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है। |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | निर्दिष्ट नाम और प्रकार वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है। |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


नया उदाहरण प्रारंभ करता है [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) क्लास का।


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है।


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - एक एनेमरेटर जिसका उपयोग संग्रह के माध्यम से इटरिट करने के लिए किया जा सकता है।

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


संग्रह में एक फ़ॉर्म फ़ील्ड सम्मिलित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | सम्मिलित करने के लिए फ़ॉर्म फ़ील्ड। |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


निर्दिष्ट नाम वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड का नाम। |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


निर्दिष्ट नाम और प्रकार वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड का नाम। |


T
: फ़ॉर्म फ़ील्ड का प्रकार।
|
| प्रकार | java.lang.Class<T> |  |

**Returns:**
T - निर्दिष्ट नाम और प्रकार वाला फ़ॉर्म फ़ील्ड, यदि पाया गया; अन्यथा, प्रकार के लिए डिफ़ॉल्ट मान।

