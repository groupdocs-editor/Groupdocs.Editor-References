---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "डॉक्यूमेंट फ़ॉर्मैट्स के लिए बेस क्लास का प्रतिनिधित्व करता है जो फ़ॉर्मैट इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

दस्तावेज़ फ़ॉर्मेट्स के लिए बेस क्लास को दर्शाता है, जो फ़ॉर्मेट इंस्टेंसेज़ के लिए सामान्य कार्यक्षमता प्रदान करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getMime()](#getMime--) | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
|
|  | [getExtension()](#getExtension--) | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
|
|  | [getFormatFamily()](#getFormatFamily--) | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फ़ैमिली से संबंधित है, उसे प्राप्त करता है। |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है। |
T
जिसमें निर्दिष्ट MIME प्रकार है।
|
|  | [hashCode()](#hashCode--) | वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है। |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है। |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | एक [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस को स्वचालित रूप से स्ट्रिंग में परिवर्तित करता है। |
|
### getMime() {#getMime--}
```
public final String getMime()
```


डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है।


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है।


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फ़ैमिली से संबंधित है, उसे प्राप्त करता है।


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


निर्दिष्ट प्रकार का एक इंस्टेंस प्राप्त करता है।
T
जिसमें निर्दिष्ट MIME प्रकार है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | दस्तावेज़ फ़ॉर्मेट का MIME प्रकार। |


T
: दस्तावेज़ फ़ॉर्मेट का प्रकार।
|

**Returns:**
T - निर्दिष्ट प्रकार T का एक इंस्टेंस, जिसमें निर्दिष्ट MIME प्रकार है।

### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान ऑब्जेक्ट के लिए एक हैश कोड लौटाता है।


**Returns:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड, जो बेस ऑब्जेक्ट, MIME प्रकार, फ़ाइल एक्सटेंशन, और फ़ॉर्मेट फ़ैमिली के हैश कोड को मिलाता है।

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | वर्तमान इंस्टेंस के साथ तुलना करने के लिए [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस। |
|

**Returns:**
boolean -  true  यदि निर्दिष्ट [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) वर्तमान इंस्टेंस के बराबर है; अन्यथा,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि क्या यह इंस्टेंस निर्दिष्ट [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | वर्तमान इंस्टेंस के साथ तुलना करने के लिए [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस। |
|

**Returns:**
boolean -  true  यदि निर्दिष्ट [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) वर्तमान इंस्टेंस के बराबर है; अन्यथा,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


एक [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस को स्वचालित रूप से स्ट्रिंग में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | परिवर्तित करने के लिए [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस। |
|

**Returns:**
java.lang.String - [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस का फ़ाइल एक्सटेंशन।

