---
title: "TiffImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "TIFF Tagged Image File Format में एक इमेज को उसके मेटाडाटा और अतिरिक्त मेथड्स के साथ दर्शाता है"
type: docs
weight: 16
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

TIFF (Tagged Image File Format) फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, इसके
मेटाडेटा और अतिरिक्त मेथड्स


*** ** * ** ***

विवरण के लिए https://en.wikipedia.org/wiki/TIFF देखें। बहुत दुर्लभ मामलों में TIFF WordProcessing दस्तावेज़ों के भीतर मौजूद हो सकता है।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | सामग्री से नया TiffImage इंस्टेंस बनाता है, जिसे इस रूप में दर्शाया गया है |
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | सामग्री से नया GifImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध TIFF छवि है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध TIFF छवि है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Tiff लौटाता है |
|
|  | [getFramesCount()](#getFramesCount--) | इस TIFF छवि के भीतर फ्रेम (छवियों) की संख्या लौटाता है। |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


सामग्री से नया TiffImage इंस्टेंस बनाता है, जिसे इस रूप में दर्शाया गया है
base64-एन्कोडेड स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | TIFF छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह TIFF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
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

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध TIFF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जिसमें संभवतः एक TIFF छवि हो सकती है। |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम में वैध TIFF छवि है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध TIFF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः TIFF छवि की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग में वैध TIFF छवि है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Tiff लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


इस TIFF छवि के भीतर फ्रेम (छवियों) की संख्या लौटाता है। यह नहीं हो सकता
1 से कम।


**Returns:**
int - 
