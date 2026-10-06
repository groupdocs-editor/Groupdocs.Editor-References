---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक स्प्रेडशीट दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

एक स्प्रेडशीट दस्तावेज़ का मेटाडेटा दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस Spreadsheet दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | टैब्स की संख्या लौटाता है |
|
|  | [getSize()](#getSize--) | इस Spreadsheet दस्तावेज़ का बाइट्स में आकार लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | यह दर्शाता है कि यह विशिष्ट Spreadsheet दस्तावेज़ एन्क्रिप्टेड है या नहीं और |
खोलने के लिए पासवर्ड की आवश्यकता होती है
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | चयनित कार्यपत्रक का SVG छवि रूप में पूर्वावलोकन बनाता और लौटाता है |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है |
SpreadsheetDocumentInfo उदाहरण
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


इस Spreadsheet दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


टैब्स की संख्या लौटाता है


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस Spreadsheet दस्तावेज़ का बाइट्स में आकार लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


यह दर्शाता है कि यह विशिष्ट Spreadsheet दस्तावेज़ एन्क्रिप्टेड है या नहीं और
खोलने के लिए पासवर्ड की आवश्यकता होती है


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


चयनित कार्यपत्रक का SVG छवि रूप में पूर्वावलोकन बनाता और लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | worksheetIndex | int | इच्छित कार्यपत्रक का 0-आधारित सूचकांक। 0 से कम नहीं हो सकता, इस स्प्रेडशीट में कार्यपत्रकों की संख्या से अधिक नहीं हो सकता। |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है
SpreadsheetDocumentInfo उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | इसके बराबरता की जाँच के लिए अन्य SpreadsheetDocumentInfo उदाहरण |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

