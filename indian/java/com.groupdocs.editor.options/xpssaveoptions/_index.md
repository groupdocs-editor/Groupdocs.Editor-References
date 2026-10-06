---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "XPS XML पेपर स्पेसिफिकेशन दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 54
url: /hi/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

XPS (XML Paper Specifications) दस्तावेज़ उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

<br />

*** ** * ** ***

एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा निर्मित XML पेपर स्पेसिफिकेशन्स पर आधारित होती हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ाइल फ़ॉर्मेट के समान है, लेकिन यह दस्तावेज़ के लेआउट, रूप-रंग और प्रिंटिंग जानकारी में XML का उपयोग करता है।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी XPS दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार। |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी XPS दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार।
डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)।


**Returns:**
बाइट
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को true सेट करने से बड़े दस्तावेज़ जनरेट करते समय मेमोरी खपत में काफी कमी आ सकती है, लेकिन सहेजने का समय धीमा हो जाता है।
डिफ़ॉल्ट रूप से false है (बेहतर प्रदर्शन के लिए मेमोरी अनुकूलन अक्षम किया गया है)।


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को true सेट करने से बड़े दस्तावेज़ जनरेट करते समय मेमोरी खपत में काफी कमी आ सकती है, लेकिन सहेजने का समय धीमा हो जाता है।
डिफ़ॉल्ट रूप से false है (बेहतर प्रदर्शन के लिए मेमोरी अनुकूलन अक्षम किया गया है)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

