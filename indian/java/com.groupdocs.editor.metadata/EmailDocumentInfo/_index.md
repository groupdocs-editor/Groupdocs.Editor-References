---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी समर्थित ईमेल फ़ॉर्मेट के एक ईमेल दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

किसी भी समर्थित ईमेल फ़ॉर्मेट के एक ईमेल दस्तावेज़ का मेटाडेटा दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस email दस्तावेज़ का फ़ॉर्मेट लौटाता है |
|
|  | [getPageCount()](#getPageCount--) | हमेशा 1 लौटाता है, क्योंकि email दस्तावेज़ों में पृष्ठीय दृश्य नहीं होता |
|
|  | [getSize()](#getSize--) | इस email दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | क्योंकि email दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह गुण हमेशा 'false' लौटाता है |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अन्य EmailDocumentInfo उदाहरण के बराबर है या नहीं |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


इस email दस्तावेज़ का फ़ॉर्मेट लौटाता है


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


हमेशा 1 लौटाता है, क्योंकि email दस्तावेज़ों में पृष्ठीय दृश्य नहीं होता


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस email दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


क्योंकि email दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह गुण हमेशा 'false' लौटाता है


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अन्य EmailDocumentInfo उदाहरण के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | इसके बराबरता की जाँच के लिए अन्य EmailDocumentInfo उदाहरण |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

