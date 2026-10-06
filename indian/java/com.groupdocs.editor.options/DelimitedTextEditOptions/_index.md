---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ (CSV, टैब-आधारित आदि) को लोड करने के विकल्प जो एक विभाजक (सेपरेटर) का उपयोग करते हैं"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ (CSV, टैब-आधारित आदि) को लोड करने के विकल्प,
जो एक विभाजक (सेपरेटर) का उपयोग करते हैं


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | विलंबित टेक्स्ट के लिए आवश्यक विकल्प वर्ग का एक इंस्टेंस बनाता है |
सेपरेटर (डिलिमिटर)
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
स्प्रेडशीट दस्तावेज़
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
स्प्रेडशीट दस्तावेज़
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग |
दस्तावेज़ को तिथि डेटा में परिवर्तित किया जाता है।
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग |
दस्तावेज़ को तिथि डेटा में परिवर्तित किया जाता है।
|
|  | [getConvertNumericData()](#getConvertNumericData--) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग |
दस्तावेज़ को संख्यात्मक डेटा में परिवर्तित किया जाता है।
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग |
दस्तावेज़ को संख्यात्मक डेटा में परिवर्तित किया जाता है।
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | परिभाषित करता है कि क्रमिक डिलिमिटर को एक के रूप में माना जाना चाहिए या नहीं। |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | परिभाषित करता है कि क्रमिक डिलिमिटर को एक के रूप में माना जाना चाहिए या नहीं। |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है, |
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ।
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मेकेनिज़्म सक्षम करता है, |
जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर
हाथ से मेमोरी उपयोग घटाएँ।
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


विलंबित टेक्स्ट के लिए आवश्यक विकल्प वर्ग का एक इंस्टेंस बनाता है
सेपरेटर (डिलिमिटर)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | सेपरेटर | java.lang.String | अनिवार्य विभाजक (डिलिमिटर), जो NULL या खाली नहीं हो सकता |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है
स्प्रेडशीट दस्तावेज़


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है
स्प्रेडशीट दस्तावेज़


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग
दस्तावेज़ को तिथि डेटा में परिवर्तित किया जाता है। डिफ़ॉल्ट false है।


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग
दस्तावेज़ को तिथि डेटा में परिवर्तित किया जाता है। डिफ़ॉल्ट false है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग
दस्तावेज़ को संख्यात्मक डेटा में परिवर्तित किया जाता है। डिफ़ॉल्ट false है।


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट-आधारित स्ट्रिंग
दस्तावेज़ को संख्यात्मक डेटा में परिवर्तित किया जाता है। डिफ़ॉल्ट false है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


परिभाषित करता है कि क्रमिक डिलिमिटर को एक के रूप में माना जाए या नहीं। By
डिफ़ॉल्ट false है।


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


परिभाषित करता है कि क्रमिक डिलिमिटर को एक के रूप में माना जाए या नहीं। By
डिफ़ॉल्ट false है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

