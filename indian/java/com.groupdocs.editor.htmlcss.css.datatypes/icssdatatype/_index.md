---
title: "ICssDataType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी CSS डेटा प्रकारों के लिए सामान्य इंटरफ़ेस जो CSS गुणों में उपयोग होते हैं"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

सभी CSS डेटा टाइप्स के लिए सामान्य इंटरफ़ेस, जो CSS प्रॉपर्टीज़ में उपयोग होते हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | वर्तमान मान का डिफ़ॉल्ट स्ट्रिंग प्रतिनिधित्व लौटाना चाहिए |
डेटा प्रकार
|
|  | [isDefault()](#isDefault--) | परिभाषित करना चाहिए कि डेटा प्रकार का वर्तमान मान डिफ़ॉल्ट है या नहीं |
इस विशिष्ट डेटा प्रकार के लिए मान है या नहीं
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


वर्तमान मान का डिफ़ॉल्ट स्ट्रिंग प्रतिनिधित्व लौटाना चाहिए
डेटा प्रकार


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


परिभाषित करना चाहिए कि डेटा प्रकार का वर्तमान मान डिफ़ॉल्ट है या नहीं
इस विशिष्ट डेटा प्रकार के लिए मान है या नहीं


**Returns:**
boolean -
