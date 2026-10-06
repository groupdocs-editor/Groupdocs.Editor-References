---
title: "BmpImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "BMP BitMap Picture फ़ॉर्मेट में एक छवि को उसके मेटाडेटा और अतिरिक्त मेथड्स के साथ दर्शाता है"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

BMP (BitMap Picture) फ़ॉर्मेट में एक छवि को उसके मेटाडेटा और
अतिरिक्त मेथड्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | सामग्री से नया BmpImage इंस्टेंस बनाता है, जिसे base64-एन्कोडेड के रूप में दर्शाया गया है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | सामग्री से नया BmpImage उदाहरण बनाता है, जिसे बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध BMP छवि है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध BMP छवि है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Bmp लौटाता है |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


सामग्री से नया BmpImage इंस्टेंस बनाता है, जिसे base64-एन्कोडेड के रूप में दर्शाया गया है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | BMP छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह BMP सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


सामग्री से नया BmpImage उदाहरण बनाता है, जिसे बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | BMP छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध BMP छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जिसमें संभवतः BMP छवि हो सकती है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम वैध BMP छवि रखती है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध BMP छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः BMP छवि की सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग वैध BMP छवि रखती है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Bmp लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
