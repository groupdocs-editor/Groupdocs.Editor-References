---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs इवेंट के लिए डेटा प्रदान करता है।"
type: docs
weight: 22
url: /hi/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

डेटा प्रदान करता है

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

इवेंट।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | फ़ाइल नाम प्राप्त करता है या सेट करता है (जैसा कि मार्कडाउन दस्तावेज़ में है) जो होगा |
प्रक्रिया।
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | फ़ाइल नाम प्राप्त करता है या सेट करता है (जैसा कि मार्कडाउन दस्तावेज़ में है) जो होगा |
प्रक्रिया।
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | एक मान प्राप्त करें जो दर्शाता है कि क्या इस छवि का निरपेक्ष URI लिंक है। |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | एक मान प्राप्त करें जो दर्शाता है कि क्या इस छवि का निरपेक्ष URI लिंक है। |
|
|  | [setData(byte[] data)](#setData-byte---) | संसाधन का उपयोगकर्ता द्वारा प्रदान किया गया डेटा सेट करता है जो उपयोग किया जाता है यदि |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


फ़ाइल नाम प्राप्त करता है या सेट करता है (जैसा कि मार्कडाउन दस्तावेज़ में है) जो होगा
प्रक्रिया।


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


फ़ाइल नाम प्राप्त करता है या सेट करता है (जैसा कि मार्कडाउन दस्तावेज़ में है) जो होगा
प्रक्रिया।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


एक मान प्राप्त करें जो दर्शाता है कि क्या इस छवि का निरपेक्ष URI लिंक है।
मान:  true  यदि इस छवि का निरपेक्ष URI लिंक है; अन्यथा,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


एक मान प्राप्त करें जो दर्शाता है कि क्या इस छवि का निरपेक्ष URI लिंक है।
मान:  true  यदि इस छवि का निरपेक्ष URI लिंक है; अन्यथा,  false .


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


संसाधन का उपयोगकर्ता द्वारा प्रदान किया गया डेटा सेट करता है जो उपयोग किया जाता है यदि

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | byte[] |  |

