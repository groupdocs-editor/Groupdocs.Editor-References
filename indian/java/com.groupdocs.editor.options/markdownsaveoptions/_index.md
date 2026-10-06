---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मार्कडाउन दस्तावेज़ों को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

मार्कडाउन दस्तावेज़ों को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

<br />

*** ** * ** ***

जब EditableDocument क्लास का एक इंस्टेंस हो, जिसमें संपादित दस्तावेज़ सामग्री हो, तो उपयोगकर्ता को MarkdownSaveOptions क्लास को लागू करना चाहिए, और यह नई मार्कडाउन फ़ॉर्मेट के दस्तावेज़ में इस सामग्री को सहेजने के लिए आवश्यक है।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow यह निर्दिष्ट करता है कि मार्कडाउन फ़ॉर्मेट में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित किया जाए। |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow यह निर्दिष्ट करता है कि मार्कडाउन फ़ॉर्मेट में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित किया जाए। |
|
|  | [getImagesFolder()](#getImagesFolder--) | जब दस्तावेज़ को निर्यात किया जाता है तो छवियों को सहेजने वाले भौतिक फ़ोल्डर को निर्दिष्ट करता है |
मार्कडाउन फ़ॉर्मेट में।
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | जब दस्तावेज़ को निर्यात किया जाता है तो छवियों को सहेजने वाले भौतिक फ़ोल्डर को निर्दिष्ट करता है |
मार्कडाउन फ़ॉर्मेट में।
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | निर्दिष्ट करता है कि क्या छवियों को आउटपुट फ़ाइल में Base64 फ़ॉर्मेट में सहेजा जाता है। |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | निर्दिष्ट करता है कि क्या छवियों को आउटपुट फ़ाइल में Base64 फ़ॉर्मेट में सहेजा जाता है। |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को सेट करना
true
बड़े दस्तावेज़ उत्पन्न करते समय मेमोरी खपत को काफी कम कर सकता है, लेकिन इसके बदले सहेजने का समय धीमा हो जाता है।
डिफ़ॉल्ट है
false
(बेहतर प्रदर्शन के लिए मेमोरी अनुकूलन अक्षम किया गया है)।


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी अनुकूलन तंत्र को सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को सेट करना
true
बड़े दस्तावेज़ उत्पन्न करते समय मेमोरी खपत को काफी कम कर सकता है, लेकिन इसके बदले सहेजने का समय धीमा हो जाता है।
डिफ़ॉल्ट है
false
(बेहतर प्रदर्शन के लिए मेमोरी अनुकूलन अक्षम किया गया है)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow यह निर्दिष्ट करता है कि मार्कडाउन फ़ॉर्मेट में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित किया जाए।
डिफ़ॉल्ट मान है [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
मान: तालिका सामग्री संरेखण


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow यह निर्दिष्ट करता है कि मार्कडाउन फ़ॉर्मेट में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित किया जाए।
डिफ़ॉल्ट मान है [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
मान: तालिका सामग्री संरेखण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


जब दस्तावेज़ को निर्यात किया जाता है तो छवियों को सहेजने वाले भौतिक फ़ोल्डर को निर्दिष्ट करता है
मार्कडाउन फ़ॉर्मेट में। डिफ़ॉल्ट मान null है।

<br />

*** ** * ** ***

यदि उपयोगकर्ता द्वारा न तो ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) और न ही ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) निर्दिष्ट किया गया है, तो GroupDocs.Editor स्वयं ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) निर्धारित करने का प्रयास करेगा और सफल होने पर इसे लागू करेगा।

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


जब दस्तावेज़ को निर्यात किया जाता है तो छवियों को सहेजने वाले भौतिक फ़ोल्डर को निर्दिष्ट करता है
मार्कडाउन फ़ॉर्मेट में। डिफ़ॉल्ट मान null है।

<br />

*** ** * ** ***

यदि उपयोगकर्ता द्वारा न तो ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) और न ही ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) निर्दिष्ट किया गया है, तो GroupDocs.Editor स्वयं ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) निर्धारित करने का प्रयास करेगा और सफल होने पर इसे लागू करेगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


निर्दिष्ट करता है कि क्या छवियों को Base64 प्रारूप में आउटपुट फ़ाइल में सहेजा जाता है। डिफ़ॉल्ट है
false
.

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को  true  पर सेट किया जाता है, तो छवि डेटा सीधे इमेज एलिमेंट्स ![](../) में निर्यात किया जाता है और अलग फ़ाइलें नहीं बनाई जातीं। यह प्रॉपर्टी, यदि true पर सेट की जाती है, तो MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) प्रॉपर्टी की तुलना में उच्च प्राथमिकता रखती है।

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


निर्दिष्ट करता है कि क्या छवियों को Base64 प्रारूप में आउटपुट फ़ाइल में सहेजा जाता है। डिफ़ॉल्ट है
false
.

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को  true  पर सेट किया जाता है, तो छवि डेटा सीधे इमेज एलिमेंट्स ![](../) में निर्यात किया जाता है और अलग फ़ाइलें नहीं बनाई जातीं। यह प्रॉपर्टी, यदि true पर सेट की जाती है, तो MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) प्रॉपर्टी की तुलना में उच्च प्राथमिकता रखती है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

