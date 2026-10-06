---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित ई-बुक फ़ॉर्मैट ePub, MOBI और AZW3 में दस्तावेज़ उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

सभी समर्थित ई-बुक फ़ॉर्मेट्स (ePub, MOBI, और AZW3) में दस्तावेज़ को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

<br />

*** ** * ** ***

समर्थित ई-बुक फ़ॉर्मैट:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (इलेक्ट्रॉनिक प्रकाशन)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle फ़ॉर्मैट 8t)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | यह पैरामीटरलेस कंस्ट्रक्टर EbookSaveOptions का नया इंस्टेंस ePub आउटपुट फ़ॉर्मैट के साथ बनाता है (फिर इसे माध्यम से संशोधित किया जा सकता है |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | निर्दिष्ट अनिवार्य e-Book आउटपुट फ़ॉर्मैट के साथ [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) का नया इंस्टेंस बनाता है, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट हैं |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | निर्णय करता है कि परिणामस्वरूप फ़ाइल में बिल्ट‑इन और कस्टम दस्तावेज़ प्रॉपर्टी निर्यात की जाएँ या नहीं। |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | निर्णय करता है कि परिणामस्वरूप फ़ाइल में बिल्ट‑इन और कस्टम दस्तावेज़ प्रॉपर्टी निर्यात की जाएँ या नहीं। |
|
|  | [getOutputFormat()](#getOutputFormat--) | परिणामस्वरूप e-Book फ़ाइल का फ़ॉर्मैट निर्दिष्ट करता है: IDPF ePub, MOBI, या AZW3। |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | परिणामस्वरूप e-Book फ़ाइल का फ़ॉर्मैट निर्दिष्ट करता है: IDPF ePub, MOBI, या AZW3। |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


यह पैरामीटरलेस कंस्ट्रक्टर EbookSaveOptions का नया इंस्टेंस ePub आउटपुट फ़ॉर्मैट के साथ बनाता है (फिर इसे माध्यम से संशोधित किया जा सकता है
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


निर्दिष्ट अनिवार्य e-Book आउटपुट फ़ॉर्मैट के साथ [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) का नया इंस्टेंस बनाता है, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | अनिवार्य आउटपुट फ़ॉर्मैट, जिसमें e-Book सहेजा जाना चाहिए |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है
2
.
इसे सेट करना
0
स्प्लिटिंग को निष्क्रिय कर देगा, इसलिए ई-बुक की सभी सामग्री परिणामी फ़ाइल के भीतर एक ही पैकेज में सम्मिलित हो जाएगी।

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को 1 से 9 के मान पर सेट किया जाता है, तो दस्तावेज़ को उन पैराग्राफ़ों पर विभाजित किया जाएगा जो उपयोग करके स्वरूपित हैं

**Heading 1**
,
**Heading 2**
,
**Heading 3**
इत्यादि शैलियों को निर्दिष्ट हेडिंग स्तर तक।

डिफ़ॉल्ट रूप से, केवल
**Heading 1**
और
**Heading 2**
पैराग्राफ़ दस्तावेज़ को विभाजित करने का कारण बनते हैं।
इस प्रॉपर्टी को शून्य (या शून्य से कम) पर सेट करने से दस्तावेज़ हेडिंग पैराग्राफ़ों पर बिल्कुल भी विभाजित नहीं होगा।

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है
2
.
इसे सेट करना
0
स्प्लिटिंग को निष्क्रिय कर देगा, इसलिए ई-बुक की सभी सामग्री परिणामी फ़ाइल के भीतर एक ही पैकेज में सम्मिलित हो जाएगी।

<br />

*** ** * ** ***

जब इस प्रॉपर्टी को 1 से 9 के मान पर सेट किया जाता है, तो दस्तावेज़ को उन पैराग्राफ़ों पर विभाजित किया जाएगा जो उपयोग करके स्वरूपित हैं

**Heading 1**
,
**Heading 2**
,
**Heading 3**
इत्यादि शैलियों को निर्दिष्ट हेडिंग स्तर तक।

डिफ़ॉल्ट रूप से, केवल
**Heading 1**
और
**Heading 2**
पैराग्राफ़ दस्तावेज़ को विभाजित करने का कारण बनते हैं।
इस प्रॉपर्टी को शून्य (या शून्य से कम) पर सेट करने से दस्तावेज़ हेडिंग पैराग्राफ़ों पर बिल्कुल भी विभाजित नहीं होगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


निर्णय करता है कि परिणामस्वरूप फ़ाइल में बिल्ट‑इन और कस्टम दस्तावेज़ प्रॉपर्टी निर्यात की जाएँ या नहीं।
डिफ़ॉल्ट मान है
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


निर्णय करता है कि परिणामस्वरूप फ़ाइल में बिल्ट‑इन और कस्टम दस्तावेज़ प्रॉपर्टी निर्यात की जाएँ या नहीं।
डिफ़ॉल्ट मान है
false
.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


परिणामस्वरूप e-Book फ़ाइल का फ़ॉर्मैट निर्दिष्ट करता है: IDPF ePub, MOBI, या AZW3।


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


परिणामस्वरूप e-Book फ़ाइल का फ़ॉर्मैट निर्दिष्ट करता है: IDPF ePub, MOBI, या AZW3।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

