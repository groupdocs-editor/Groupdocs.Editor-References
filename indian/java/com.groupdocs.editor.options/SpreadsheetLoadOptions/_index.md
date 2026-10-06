---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "XLSX, ODS आदि जैसे बाइनरी स्प्रेडशीट सेल्स एक्सेल-संगत दस्तावेज़ लोड करने के विकल्प शामिल करता है।"
type: docs
weight: 36
url: /hi/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

बाइनरी स्प्रेडशीट (सेल्स, एक्सेल-संगत) लोड करने के विकल्प शामिल करता है।
दस्तावेज़ जैसे XLS(X), ODS आदि को एडिटर क्लास में लोड करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | डिफ़ॉल्ट पैरामीटरलेस कंस्ट्रक्टर - सभी पैरामीटरों के डिफ़ॉल्ट मान होते हैं। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
स्प्रेडशीट दस्तावेज़ को खोलते समय, यदि वह एन्कोडेड है।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
स्प्रेडशीट दस्तावेज़ को खोलते समय, यदि वह एन्कोडेड है।
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है, |
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ।
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है, |
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ।
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


डिफ़ॉल्ट पैरामीटरलेस कंस्ट्रक्टर - सभी पैरामीटरों के डिफ़ॉल्ट मान होते हैं।


### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
यदि स्प्रेडशीट दस्तावेज़ एन्कोडेड है, तो उसे खोलना। इसे NULL या खाली सेट करें।
पासवर्ड का उपयोग न करने के लिए स्ट्रिंग (डिफ़ॉल्ट मान)।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
यदि स्प्रेडशीट दस्तावेज़ एन्कोडेड है, तो उसे खोलना। इसे NULL या खाली सेट करें।
पासवर्ड का उपयोग न करने के लिए स्ट्रिंग (डिफ़ॉल्ट मान)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है,
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ। बड़े दस्तावेज़ों को प्रोसेस करते समय उपयोगी और
OutOfMemoryException का सामना करते हुए। डिफ़ॉल्ट false है (मेमोरी अनुकूलन है
बेहतर प्रदर्शन के लिए अक्षम किया गया है)।


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है,
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ। बड़े दस्तावेज़ों को प्रोसेस करते समय उपयोगी और
OutOfMemoryException का सामना करते हुए। डिफ़ॉल्ट false है (मेमोरी अनुकूलन है
बेहतर प्रदर्शन के लिए अक्षम किया गया है)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

