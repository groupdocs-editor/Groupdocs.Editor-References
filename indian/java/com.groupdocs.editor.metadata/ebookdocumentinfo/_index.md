---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक ईबुक दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

एक ईबुक दस्तावेज़ का मेटाडेटा दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | MOBI या AZW3 के मामले में पृष्ठों की संख्या या ePub के मामले में अध्यायों की संख्या लौटाता है। |
|
|  | [getSize()](#getSize--) | इस eBook दस्तावेज़ का आकार बाइट्स में लौटाता है। |
|
|  | [isEncrypted()](#isEncrypted--) | क्योंकि eBook दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह प्रॉपर्टी हमेशा 'false' लौटाती है। |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अन्य EbookDocumentInfo इंस्टेंस के बराबर है या नहीं। |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


इस दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


MOBI या AZW3 के मामले में पृष्ठों की संख्या या ePub के मामले में अध्यायों की संख्या लौटाता है।

<br />

*** ** * ** ***

eBook दस्तावेज़ आमतौर पर स्थिर पृष्ठ नहीं रखते और इसलिए पृष्ठ गणना नहीं होती। ePub के मामले में अध्यायों की संख्या की गणना संभव है। हालांकि, MOBI और AZW3 फ़ॉर्मेट में भी कोई अध्याय नहीं होते, इसलिए यह संख्या मानक पृष्ठ आकार A4, पोर्ट्रेट अभिविन्यास में सेट करके गणना की जाती है।

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस eBook दस्तावेज़ का आकार बाइट्स में लौटाता है।


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


क्योंकि eBook दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह प्रॉपर्टी हमेशा 'false' लौटाती है।


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अन्य EbookDocumentInfo इंस्टेंस के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | अन्य EbookDocumentInfo इंस्टेंस, जिसे इस के साथ समानता के लिए जाँचना चाहिए। |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

