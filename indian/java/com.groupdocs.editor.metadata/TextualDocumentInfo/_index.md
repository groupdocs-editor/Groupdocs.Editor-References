---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक टेक्स्टुअल दस्तावेज़ जैसे XML, HTML या साधारण टेक्स्ट TXT का मेटाडाटा दर्शाता है"
type: docs
weight: 16
url: /hi/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

एक टेक्स्टुअल दस्तावेज़ जैसे XML, HTML या साधारण टेक्स्ट का मेटाडाटा दर्शाता है
(TXT)

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | इस टेक्स्टुअल दस्तावेज़ का फ़ॉर्मेट लौटाता है। |
|
|  | [getPageCount()](#getPageCount--) | हमेशा 1 लौटाता है |
|
|  | [getSize()](#getSize--) | इस टेक्स्टुअल का बाइट्स में आकार लौटाता है (अक्षरों की संख्या नहीं) |
दस्तावेज़
|
|  | [isEncrypted()](#isEncrypted--) | हमेशा 'false' लौटाता है, क्योंकि टेक्स्टुअल दस्तावेज़ एन्क्रिप्ट नहीं किए जा सकते। |
|
|  | [getEncoding()](#getEncoding--) | टेक्स्ट दस्तावेज़ की अनुमानित एन्कोडिंग लौटाता है |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


इस टेक्स्टुअल दस्तावेज़ का फ़ॉर्मेट लौटाता है। यह 100% सही नहीं हो सकता
कुछ मामलों में।


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


हमेशा 1 लौटाता है


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


इस टेक्स्टुअल का बाइट्स में आकार लौटाता है (अक्षरों की संख्या नहीं)
दस्तावेज़


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


हमेशा 'false' लौटाता है, क्योंकि टेक्स्टुअल दस्तावेज़ एन्क्रिप्ट नहीं किए जा सकते।


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


टेक्स्ट दस्तावेज़ की अनुमानित एन्कोडिंग लौटाता है


**Returns:**
java.nio.charset.Charset
