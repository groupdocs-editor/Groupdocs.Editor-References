---
title: "ImageType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक समर्थित इमेज टाइप फ़ॉर्मेट का प्रतिनिधित्व करता है जो रास्टर और वेक्टर दोनों फ़ॉर्मेट को समर्थन देता है"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

एक समर्थित इमेज प्रकार (फ़ॉर्मेट) को दर्शाता है, जो रास्टर और वेक्टर दोनों फ़ॉर्मेट को समर्थन देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | अपरिभाषित इमेज टाइप - विशेष मान, जो सामान्यतः नहीं होना चाहिए |
|
|  | [getJpeg()](#getJpeg--) | JPEG इमेज टाइप |
|
|  | [getPng()](#getPng--) | PNG इमेज टाइप |
|
|  | [getBmp()](#getBmp--) | BMP इमेज टाइप |
|
|  | [getGif()](#getGif--) | GIF इमेज टाइप |
|
|  | [getIcon()](#getIcon--) | ICON इमेज टाइप |
|
|  | [getSvg()](#getSvg--) | SVG वेक्टर छवि प्रकार |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) वेक्टर छवि प्रकार |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) वेक्टर छवि प्रकार |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) रास्टर छवि प्रकार |
|
|  | [getFormalName()](#getFormalName--) | इस छवि फ़ॉर्मेट का औपचारिक नाम लौटाता है। |
|
|  | [isVector()](#isVector--) | यह दर्शाता है कि यह विशेष फ़ॉर्मेट वेक्टर (सही) है या रास्टर |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | किसी विशेष छवि प्रकार का फ़ाइल एक्सटेंशन (आगे बिंदु के बिना) |
छोटे अक्षरों में।
|
|  | [toString()](#toString--) | FormalName प्रॉपर्टी लौटाता है |
|
|  | [getMimeCode()](#getMimeCode--) | किसी विशेष छवि प्रकार का MIME कोड स्ट्रिंग के रूप में। |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "ImageType" के बराबर है या नहीं |
उदाहरण
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, |
जो संभवतः एक अन्य "ImageType" इंस्टेंस है
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस बराबर हैं या नहीं |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस असमान हैं या नहीं |
|
|  | [hashCode()](#hashCode--) | हैश-कोड लौटाता है, जो इस विशिष्ट के लिए अपरिवर्तनीय संख्या है |
उदाहरण
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | ImageType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के समतुल्य है, जो |
निर्दिष्ट फ़ाइलनाम से निकाला गया है
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | ImageType मान लौटाता है, जो निर्दिष्ट MIME कोड के समतुल्य है |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


अपरिभाषित इमेज टाइप - विशेष मान, जो सामान्यतः नहीं होना चाहिए


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG इमेज टाइप


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG इमेज टाइप


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP इमेज टाइप


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF इमेज टाइप


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON इमेज टाइप


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG वेक्टर छवि प्रकार


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) वेक्टर छवि प्रकार


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) वेक्टर छवि प्रकार


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) रास्टर छवि प्रकार


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


इस छवि फ़ॉर्मेट का औपचारिक नाम लौटाता है। कभी NULL नहीं लौटाता। यदि
इंस्टेंस भ्रष्ट नहीं है, कभी अपवाद नहीं फेंकता।


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


यह दर्शाता है कि यह विशेष फ़ॉर्मेट वेक्टर (सही) है या रास्टर
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


किसी विशेष छवि प्रकार का फ़ाइल एक्सटेंशन (आगे बिंदु के बिना)
छोटे अक्षरों में। Undefined प्रकार के लिए स्ट्रिंग 'unsefined' लौटाता है।


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


FormalName प्रॉपर्टी लौटाता है


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


किसी विशेष छवि प्रकार का MIME कोड स्ट्रिंग के रूप में। Undefined प्रकार के लिए
स्ट्रिंग 'unsefined' लौटाता है।


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "ImageType" के बराबर है या नहीं
उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | इसके बराबरता की जाँच के लिए अन्य ImageType इंस्टेंस |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं,
जो संभवतः एक अन्य "ImageType" इंस्टेंस है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य System.Object उदाहरण, जो संभवतः ImageType प्रकार का है, इस के साथ समानता की जाँच के लिए |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस बराबर हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | पहला ImageType उदाहरण जाँच के लिए |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | दूसरा ImageType उदाहरण जाँच के लिए |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस असमान हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | पहला ImageType उदाहरण जाँच के लिए |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | दूसरा ImageType उदाहरण जाँच के लिए |
|

**Returns:**
boolean - यदि असमान हों तो True, यदि समान हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


हैश-कोड लौटाता है, जो इस विशिष्ट के लिए अपरिवर्तनीय संख्या है
उदाहरण


**Returns:**
int - साइन किया गया 4-बाइट पूर्णांक

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


ImageType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के समतुल्य है, जो
निर्दिष्ट फ़ाइलनाम से निकाला गया है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइलनाम | java.lang.String | मनमाना फ़ाइलनाम, यह सापेक्ष या पूर्ण पथ हो सकता है |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


ImageType मान लौटाता है, जो निर्दिष्ट MIME कोड के समतुल्य है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | mimeCode | java.lang.String | मनमाना MIME-कोड |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

