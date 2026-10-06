---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक मार्कडाउन दस्तावेज़ का मेटाडेटा दर्शाता है"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

एक मार्कडाउन दस्तावेज़ का मेटाडेटा दर्शाता है

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस Markdown दस्तावेज़ का फ़ॉर्मेट लौटाता है — हमेशा यही होता है |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | पृष्ठों की संख्या लौटाता है। |
|
|  | [getSize()](#getSize--) | इस Markdown दस्तावेज़ का आकार बाइट्स में लौटाता है |
|
|  | [isEncrypted()](#isEncrypted--) | क्योंकि Markdown दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह |
प्रॉपर्टी हमेशा 'false' लौटाती है
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


इस Markdown दस्तावेज़ का फ़ॉर्मेट लौटाता है — हमेशा यही होता है
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


पृष्ठों की संख्या लौटाता है। Markdown दस्तावेज़ आमतौर पर स्थिर पृष्ठ नहीं रखते
और इस प्रकार पृष्ठ गणना, इसलिए यह संख्या मानक पृष्ठ आकार से गणना की जाती है
पोर्ट्रेट अभिविन्यास में A4 पर सेट किया गया है।


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस Markdown दस्तावेज़ का आकार बाइट्स में लौटाता है


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


क्योंकि Markdown दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह
प्रॉपर्टी हमेशा 'false' लौटाती है


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट अन्य के बराबर है
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | अन्य [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) इंस्टेंस, जिसे इस के साथ समानता के लिए जांचा जाना चाहिए |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

