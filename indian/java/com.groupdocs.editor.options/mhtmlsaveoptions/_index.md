---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "समग्र HTML दस्तावेज़ों की MHTML MIME संलग्नक को उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 26
url: /hi/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

MHTML (MIME एन्कैप्सुलेशन ऑफ एग्रीगेट HTML डॉक्यूमेंट्स) दस्तावेज़ों को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URL का उपयोग किया जाए। |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URL का उपयोग किया जाए। |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | निर्दिष्ट करता है कि क्या अंतर्निहित और कस्टम दस्तावेज़ गुणों को MHTML में निर्यात किया जाए। |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | निर्दिष्ट करता है कि क्या अंतर्निहित और कस्टम दस्तावेज़ गुणों को MHTML में निर्यात किया जाए। |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | निर्दिष्ट करता है कि क्या भाषा जानकारी को MHTML में निर्यात किया जाए। |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | निर्दिष्ट करता है कि क्या भाषा जानकारी को MHTML में निर्यात किया जाए। |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URL का उपयोग किया जाए। डिफ़ॉल्ट मान है
false
.

<br />

*** ** * ** ***


डिफ़ॉल्ट रूप से, MHTML दस्तावेज़ों में संसाधनों को फ़ाइल नाम (उदाहरण के लिए, "image.png") द्वारा संदर्भित किया जाता है, जो MIME भागों के "Content-Location" हेडर से मेल खाते हैं। यह विकल्प एक वैकल्पिक विधि को सक्षम करता है, जहाँ संसाधन फ़ाइलों के संदर्भ को CID (Content-ID) URL (उदाहरण के लिए, "cid:image.png") के रूप में लिखा जाता है और "Content-ID" हेडर से मेल खाता है।


सिद्धांत में, दो संदर्भ विधियों के बीच कोई अंतर नहीं होना चाहिए और दोनों में से कोई भी किसी भी ब्राउज़र या मेल एजेंट में ठीक से काम करना चाहिए। व्यवहार में, हालांकि, कुछ एजेंट फ़ाइल नाम द्वारा संसाधनों को प्राप्त करने में विफल होते हैं। यदि आपका ब्राउज़र या मेल एजेंट MTHML दस्तावेज़ में शामिल संसाधनों को लोड करने से इनकार करता है (छवियां नहीं दिखाता या CSS शैली लोड नहीं करता), तो CID URL के साथ दस्तावेज़ को निर्यात करने का प्रयास करें।

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URL का उपयोग किया जाए। डिफ़ॉल्ट मान है
false
.

<br />

*** ** * ** ***


डिफ़ॉल्ट रूप से, MHTML दस्तावेज़ों में संसाधनों को फ़ाइल नाम (उदाहरण के लिए, "image.png") द्वारा संदर्भित किया जाता है, जो MIME भागों के "Content-Location" हेडर से मेल खाते हैं। यह विकल्प एक वैकल्पिक विधि को सक्षम करता है, जहाँ संसाधन फ़ाइलों के संदर्भ को CID (Content-ID) URL (उदाहरण के लिए, "cid:image.png") के रूप में लिखा जाता है और "Content-ID" हेडर से मेल खाता है।


सिद्धांत में, दो संदर्भ विधियों के बीच कोई अंतर नहीं होना चाहिए और दोनों में से कोई भी किसी भी ब्राउज़र या मेल एजेंट में ठीक से काम करना चाहिए। व्यवहार में, हालांकि, कुछ एजेंट फ़ाइल नाम द्वारा संसाधनों को प्राप्त करने में विफल होते हैं। यदि आपका ब्राउज़र या मेल एजेंट MTHML दस्तावेज़ में शामिल संसाधनों को लोड करने से इनकार करता है (छवियां नहीं दिखाता या CSS शैली लोड नहीं करता), तो CID URL के साथ दस्तावेज़ को निर्यात करने का प्रयास करें।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


निर्दिष्ट करता है कि क्या अंतर्निहित और कस्टम दस्तावेज़ गुणों को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान है
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


निर्दिष्ट करता है कि क्या अंतर्निहित और कस्टम दस्तावेज़ गुणों को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान है
false
.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


निर्दिष्ट करता है कि क्या भाषा जानकारी को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान है
false
.

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को  true  पर सेट किया जाता है, तो GroupDocs.Editor दस्तावेज़ तत्वों पर  lang  HTML-attribute जारी करता है जो भाषा निर्दिष्ट करते हैं। यह भाषा-संबंधी अर्थ को संरक्षित करने के लिए आवश्यक हो सकता है।

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


निर्दिष्ट करता है कि क्या भाषा जानकारी को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान है
false
.

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को  true  पर सेट किया जाता है, तो GroupDocs.Editor दस्तावेज़ तत्वों पर  lang  HTML-attribute जारी करता है जो भाषा निर्दिष्ट करते हैं। यह भाषा-संबंधी अर्थ को संरक्षित करने के लिए आवश्यक हो सकता है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

