---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक वर्डप्रोसेसिंग दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 17
url: /hi/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

एक वर्डप्रोसेसिंग दस्तावेज़ का मेटाडेटा दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस WordProcessing दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | पृष्ठों की संख्या लौटाता है |
|
|  | [getSize()](#getSize--) | इस WordProcessing दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | निर्धारित करता है कि यह विशिष्ट WordProcessing दस्तावेज़ एन्क्रिप्टेड है या नहीं और |
खोलने के लिए पासवर्ड की आवश्यकता होती है
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | चयनित पृष्ठ का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है |
WordProcessingDocumentInfo उदाहरण
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


इस WordProcessing दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


पृष्ठों की संख्या लौटाता है


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस WordProcessing दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


निर्धारित करता है कि यह विशिष्ट WordProcessing दस्तावेज़ एन्क्रिप्टेड है या नहीं और
खोलने के लिए पासवर्ड की आवश्यकता होती है


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


चयनित पृष्ठ का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | pageIndex | int | वांछित पृष्ठ का 0-आधारित सूचकांक। 0 से कम नहीं हो सकता, इस WordProcessing दस्तावेज़ में पृष्ठों की संख्या से अधिक नहीं हो सकता। |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है
WordProcessingDocumentInfo उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | अन्य WordProcessingDocumentInfo उदाहरण, जिसे इस के साथ समानता के लिए जाँचा जाना चाहिए |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

