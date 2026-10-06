---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "DOCX, RTF, ODT आदि जैसे Word‑संगत WordProcessing दस्तावेज़ लोड करने के विकल्प शामिल हैं।"
type: docs
weight: 45
url: /hi/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

WordProcessing (Word‑संगत) दस्तावेज़ लोड करने के विकल्प शामिल हैं जैसे
DOC(X), RTF, ODT आदि को Editor क्लास में

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
यदि WordProcessing दस्तावेज़ एन्कोडेड है तो खोलना।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
यदि WordProcessing दस्तावेज़ एन्कोडेड है तो खोलना।
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
यदि WordProcessing दस्तावेज़ एन्कोडेड है तो खोलना। इसे NULL या खाली सेट करें
पासवर्ड का उपयोग न करने के लिए स्ट्रिंग (डिफ़ॉल्ट मान)।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
यदि WordProcessing दस्तावेज़ एन्कोडेड है तो खोलना। इसे NULL या खाली सेट करें
पासवर्ड का उपयोग न करने के लिए स्ट्रिंग (डिफ़ॉल्ट मान)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

