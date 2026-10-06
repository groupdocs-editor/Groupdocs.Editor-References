---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "JPEG Joint Photographic Experts Group फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, इसके मेटाडाटा और अतिरिक्त मेथड्स के साथ"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

JPEG (Joint Photographic Experts Group) फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, इसके साथ
इसके मेटाडाटा और अतिरिक्त मेथड्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | सामग्री से नया JpegImage इंस्टेंस बनाता है, जिसे इस रूप में दर्शाया गया है |
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | सामग्री से नया JpegImage इंस्टेंस बनाता है, जिसे बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध JPEG छवि है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध JPEG छवि है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Jpeg लौटाता है |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


सामग्री से नया JpegImage इंस्टेंस बनाता है, जिसे इस रूप में दर्शाया गया है
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | JPEG छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। यह null, खाली या whitespace नहीं हो सकता। यदि यह JPEG सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


सामग्री से नया JpegImage इंस्टेंस बनाता है, जिसे बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | JPEG छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध JPEG छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जो संभवतः एक JPEG छवि रखती है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम में वैध JPEG छवि है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध JPEG छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः JPEG छवि की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग में वैध JPEG छवि है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Jpeg लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
