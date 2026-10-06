---
title: "IconImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "ICON फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है जिसमें उसका मेटाडेटा और अतिरिक्त विधियाँ"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

ICON फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है जिसमें उसका मेटाडेटा और अतिरिक्त विधियाँ

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | कंटेंट से नया IconImage इंस्टेंस बनाता है, जो इस रूप में दर्शाया गया है |
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | कंटेंट से नया IconImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध ICON इमेज है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध ICON इमेज है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Icon लौटाता है |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | इस ICON फ़ाइल में मौजूद इमेज की संख्या लौटाता है |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


कंटेंट से नया IconImage इंस्टेंस बनाता है, जो इस रूप में दर्शाया गया है
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | ICON इमेज का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | कंटेंट को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह ICON कंटेंट नहीं है, तो एक्सेप्शन फेंका जाएगा। |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


कंटेंट से नया IconImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | ICON इमेज का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध ICON इमेज है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जिसमें संभवतः एक ICON इमेज हो सकता है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम वैध ICON इमेज रखती है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध ICON इमेज है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः ICON इमेज की कंटेंट base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग वैध ICON इमेज रखती है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Icon लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


इस ICON फ़ाइल में मौजूद इमेज की संख्या लौटाता है


**Returns:**
int
