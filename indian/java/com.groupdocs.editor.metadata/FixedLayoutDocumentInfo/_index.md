---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "PDF या XPS जैसे निश्चित लेआउट फ़ॉर्मेट वाले एक दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

PDF या XPS जैसे निश्चित लेआउट फ़ॉर्मेट वाले एक दस्तावेज़ का मेटाडेटा दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस fixed-layout फ़ॉर्मेट दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | पृष्ठों की संख्या लौटाता है |
|
|  | [getSize()](#getSize--) | इस fixed-layout फ़ॉर्मेट दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | निर्धारित करता है कि यह विशिष्ट fixed-layout फ़ॉर्मेट दस्तावेज़ एन्क्रिप्टेड है या नहीं और खोलने के लिए पासवर्ड की आवश्यकता है |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अन्य FixedLayoutDocumentInfo उदाहरण के बराबर है या नहीं |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


इस fixed-layout फ़ॉर्मेट दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


इस fixed-layout फ़ॉर्मेट दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


निर्धारित करता है कि यह विशिष्ट fixed-layout फ़ॉर्मेट दस्तावेज़ एन्क्रिप्टेड है या नहीं और खोलने के लिए पासवर्ड की आवश्यकता है


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अन्य FixedLayoutDocumentInfo उदाहरण के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | अन्य FixedLayoutDocumentInfo उदाहरण, जिसे इस के साथ समानता के लिए जाँचा जाना चाहिए |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

