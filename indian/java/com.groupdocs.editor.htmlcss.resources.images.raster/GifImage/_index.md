---
title: "GifImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "GIF ग्राफ़िक्स इंटरचेंज फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, जिसमें उसका मेटाडेटा और अतिरिक्त मेथड्स होते हैं।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

GIF (ग्राफ़िक्स इंटरचेंज फ़ॉर्मेट) फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, जिसमें उसका
मेटाडेटा और अतिरिक्त मेथड्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | सामग्री से नया GifImage इंस्टेंस बनाता है, जो base64-एन्कोडेड के रूप में दर्शाया गया है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | सामग्री से नया GifImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध GIF छवि है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध GIF छवि है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Gif लौटाता है |
|
|  | [getVersion()](#getVersion--) | इस GIF छवि का आंतरिक संस्करण लौटाता है (संस्करण निकाला गया है |
हेडर)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


सामग्री से नया GifImage इंस्टेंस बनाता है, जो base64-एन्कोडेड के रूप में दर्शाया गया है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | GIF छवि का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह GIF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


सामग्री से नया GifImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | GIF छवि का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध GIF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जिसमें संभवतः एक GIF छवि हो सकती है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम में वैध GIF छवि है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध GIF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः GIF छवि की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग में वैध GIF छवि है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Gif लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


इस GIF छवि का आंतरिक संस्करण लौटाता है (संस्करण निकाला गया है
हेडर)


**Returns:**
java.lang.String
