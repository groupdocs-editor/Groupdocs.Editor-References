---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक प्रेज़ेंटेशन दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 14
url: /hi/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

एक प्रेज़ेंटेशन दस्तावेज़ का मेटाडेटा दर्शाता है

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस Presentation दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | इस Presentation दस्तावेज़ में स्लाइडों की संख्या लौटाता है |
|
|  | [getSize()](#getSize--) | इस Presentation दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | संकेत करता है कि क्या यह विशिष्ट Presentation दस्तावेज़ एन्क्रिप्टेड है और खोलने के लिए पासवर्ड की आवश्यकता है |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | चयनित स्लाइड का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


इस Presentation दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


इस Presentation दस्तावेज़ में स्लाइडों की संख्या लौटाता है


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस Presentation दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


संकेत करता है कि क्या यह विशिष्ट Presentation दस्तावेज़ एन्क्रिप्टेड है और खोलने के लिए पासवर्ड की आवश्यकता है


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


चयनित स्लाइड का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | slideIndex | int | इच्छित स्लाइड का 0-आधारित इंडेक्स। 0 से कम नहीं हो सकता, इस प्रस्तुति में स्लाइडों की संख्या से अधिक नहीं हो सकता। |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

