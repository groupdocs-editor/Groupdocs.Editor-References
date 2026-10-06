---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "PDF पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

PDF (पोर्टेबल
डॉक्यूमेंट फ़ॉर्मेट) दस्तावेज़

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड, जो उत्पन्न PDF दस्तावेज़ पर उपयोगकर्ता पासवर्ड के रूप में लागू होगा, खोलने के लिए आवश्यक है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड, जो उत्पन्न PDF दस्तावेज़ पर उपयोगकर्ता पासवर्ड के रूप में लागू होगा, खोलने के लिए आवश्यक है। |
|
|  | [getCompliance()](#getCompliance--) | आउटपुट दस्तावेज़ों के लिए PDF मानकों के अनुपालन स्तर को निर्दिष्ट करता है। |
|
|  | [setCompliance(int value)](#setCompliance-int-) | आउटपुट दस्तावेज़ों के लिए PDF मानकों के अनुपालन स्तर को निर्दिष्ट करता है। |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी PDF दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार है। |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी PDF दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार है। |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड, जो उत्पन्न PDF दस्तावेज़ पर उपयोगकर्ता पासवर्ड के रूप में लागू होगा, खोलने के लिए आवश्यक है।
यदि NULL या खाली है, तो दस्तावेज़ पर कोई पासवर्ड लागू नहीं होगा। अन्यथा, दस्तावेज़ को RC4 (128 बिट कुंजी लंबाई) से एन्क्रिप्ट किया जाएगा।
डिफ़ॉल्ट रूप से यह NULL है — पासवर्ड लागू नहीं किया जाता।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड, जो उत्पन्न PDF दस्तावेज़ पर उपयोगकर्ता पासवर्ड के रूप में लागू होगा, खोलने के लिए आवश्यक है।
यदि NULL या खाली है, तो दस्तावेज़ पर कोई पासवर्ड लागू नहीं होगा। अन्यथा, दस्तावेज़ को RC4 (128 बिट कुंजी लंबाई) से एन्क्रिप्ट किया जाएगा।
डिफ़ॉल्ट रूप से यह NULL है — पासवर्ड लागू नहीं किया जाता।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


आउटपुट दस्तावेज़ों के लिए PDF मानकों के अनुपालन स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट रूप से PdfCompliance.Pdf17 है।


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


आउटपुट दस्तावेज़ों के लिए PDF मानकों के अनुपालन स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट रूप से PdfCompliance.Pdf17 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी PDF दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)।


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी PDF दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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

