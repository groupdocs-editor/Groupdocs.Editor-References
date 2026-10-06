---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी समर्थित वेक्टर छवि के लिए बेस क्लास"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

किसी भी समर्थित वेक्टर छवि के लिए बेस क्लास

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Fields

| Field | विवरण |
| --- | --- |
| [Disposed](#Disposed) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | इस वेक्टर इमेज का नाम लौटाता है। |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | इस वेक्टर इमेज का सही फ़ाइलनाम लौटाता है, जो नाम और |
एक्सटेंशन।
|
|  | [getAspectRatio()](#getAspectRatio--) | इस वेक्टर इमेज का आस्पेक्ट रेशियो लौटाता है |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | इस वेक्टर इमेज के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | इस इंस्टेंस को निर्दिष्ट के साथ रेफ़रेंस समानता पर जाँचता है। |
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह रास्टर इमेज डिस्पोज़्ड है या नहीं |
|
|  | [getType()](#getType--) | इम्प्लीमेंटिंग टाइप को वेक्टर के प्रकार के बारे में जानकारी लौटानी चाहिए |
इमेज
|
|  | [getByteContent()](#getByteContent--) | इम्प्लीमेंटिंग टाइप को इस वेक्टर इमेज की सामग्री बाइट के रूप में लौटानी चाहिए |
स्ट्रीम
|
|  | [getTextContent()](#getTextContent--) | इम्प्लीमेंटिंग टाइप को इस वेक्टर इमेज की सामग्री टेक्स्ट में लौटानी चाहिए |
फ़ॉर्म: इमेज प्रकार से संबंधित XML का base64-एन्कोडेड
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इम्प्लीमेंटिंग टाइप को इस इमेज को निर्दिष्ट पथ द्वारा डिस्क पर सहेजना चाहिए |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | इम्प्लीमेंटिंग टाइप को वर्तमान वेक्टर इमेज को रास्टर PNG में सहेजना चाहिए |
निर्दिष्ट बाइट स्ट्रीम में फ़ॉर्मेट करें
|
|  | [dispose()](#dispose--) | इम्प्लीमेंटिंग टाइप को इस इंस्टेंस को डिस्पोज़ करना चाहिए |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


इस वेक्टर इमेज का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम नहीं होता
एक्सटेंशन और सैद्धांतिक रूप से फ़ाइलनाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


इस वेक्टर इमेज का सही फ़ाइलनाम लौटाता है, जो नाम और
एक्सटेंशन। सैद्धांतिक रूप से नाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


इस वेक्टर इमेज का आस्पेक्ट रेशियो लौटाता है


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


इस वेक्टर इमेज के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


इस इंस्टेंस को निर्दिष्ट के साथ रेफ़रेंस समानता पर जाँचता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | वेक्टर इमेज का अन्य इंस्टेंस |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


निर्धारित करता है कि यह रास्टर इमेज डिस्पोज़्ड है या नहीं


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


इम्प्लीमेंटिंग टाइप को वेक्टर के प्रकार के बारे में जानकारी लौटानी चाहिए
इमेज


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


इम्प्लीमेंटिंग टाइप को इस वेक्टर इमेज की सामग्री बाइट के रूप में लौटानी चाहिए
स्ट्रीम


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


इम्प्लीमेंटिंग टाइप को इस वेक्टर इमेज की सामग्री टेक्स्ट में लौटानी चाहिए
फ़ॉर्म: इमेज प्रकार से संबंधित XML का base64-एन्कोडेड


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


इम्प्लीमेंटिंग टाइप को इस इमेज को निर्दिष्ट पथ द्वारा डिस्क पर सहेजना चाहिए


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


इम्प्लीमेंटिंग टाइप को वर्तमान वेक्टर इमेज को रास्टर PNG में सहेजना चाहिए
निर्दिष्ट बाइट स्ट्रीम में फ़ॉर्मेट करें


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | बाइट स्ट्रीम, जिसमें इस रास्टर इमेज का PNG संस्करण संग्रहीत किया जाएगा। NULL नहीं होना चाहिए और लिखने का समर्थन करना चाहिए। |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


इम्प्लीमेंटिंग टाइप को इस इंस्टेंस को डिस्पोज़ करना चाहिए


