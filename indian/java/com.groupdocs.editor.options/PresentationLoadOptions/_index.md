---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित प्रेजेंटेशन फ़ॉर्मैट जैसे PPTX, PPTM, PPSX आदि के दस्तावेज़ लोड करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 33
url: /hi/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

सभी समर्थित दस्तावेज़ लोड करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।
प्रेजेंटेशन फ़ॉर्मैट जैसे PPT(X), PPTM, PPS(X) आदि।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
प्रेजेंटेशन दस्तावेज़ को खोलने के लिए, यदि वह एन्कोडेड है।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
प्रेजेंटेशन दस्तावेज़ को खोलने के लिए, यदि वह एन्कोडेड है।
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
प्रेजेंटेशन दस्तावेज़ को खोलने के लिए, यदि वह एन्कोडेड है। इसे NULL या खाली स्ट्रिंग सेट करें।
पासवर्ड हटाने के लिए स्ट्रिंग।


*** ** * ** ***

डिफ़ॉल्ट रूप से इस प्रॉपर्टी का मान NULL होता है \\u2014 पासवर्ड सेट नहीं है। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित है, तो पासवर्ड अनिवार्य है और यदि पासवर्ड निर्दिष्ट नहीं किया गया या अमान्य है तो एक अपवाद फेंका जाएगा। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित नहीं है, लेकिन पासवर्ड सेट किया गया है, तो उसे अनदेखा किया जाएगा।

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
प्रेजेंटेशन दस्तावेज़ को खोलने के लिए, यदि वह एन्कोडेड है। इसे NULL या खाली स्ट्रिंग सेट करें।
पासवर्ड हटाने के लिए स्ट्रिंग।


*** ** * ** ***

डिफ़ॉल्ट रूप से इस प्रॉपर्टी का मान NULL होता है \\u2014 पासवर्ड सेट नहीं है। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित है, तो पासवर्ड अनिवार्य है और यदि पासवर्ड निर्दिष्ट नहीं किया गया या अमान्य है तो एक अपवाद फेंका जाएगा। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित नहीं है, लेकिन पासवर्ड सेट किया गया है, तो उसे अनदेखा किया जाएगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

