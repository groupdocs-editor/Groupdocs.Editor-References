---
title: "SvgImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "SVG Scalable Vector Graphics फ़ॉर्मेट में एक वेक्टर इमेज को उसके मेटाडेटा और अतिरिक्त मेथड्स के साथ दर्शाता है"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

SVG (Scalable Vector Graphics) फ़ॉर्मेट में एक वेक्टर इमेज को उसके साथ दर्शाता है
मेटाडेटा और अतिरिक्त मेथड्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | सामग्री से नया SvgImage इंस्टेंस बनाता है, जो सामान्य स्ट्रिंग के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | सामग्री से नया SvgImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | जाँच करता है कि निर्दिष्ट टेक्स्टुअल XML-अनुपालन सामग्री सतह पर सत्यापित हो |
एक SVG इमेज को दर्शाता है
|
|  | [getType()](#getType--) | ImageType.Svg लौटाता है |
|
|  | [getByteContent()](#getByteContent--) | इस SVG छवि की सामग्री को बाइनरी स्ट्रीम के रूप में लौटाता है |
|
|  | [getTextContent()](#getTextContent--) | इस SVG छवि की सामग्री को साधारण टेक्स्ट (XML प्रारूप में) के रूप में लौटाता है |
|
|  | [getXmlContent()](#getXmlContent--) | इस SVG छवि की सामग्री को उसके मूल XML‑अनुपालन रूप में लौटाता है |
पाठ्य रूप
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस SVG छवि को फ़ाइल में सहेजता है |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | इस वेक्टर SVG छवि को रास्टर PNG छवि में सहेजता है |
|
|  | [dispose()](#dispose--) | इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स को |
और प्रॉपर्टीज़ काम नहीं कर रही हैं
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


सामग्री से नया SvgImage इंस्टेंस बनाता है, जो सामान्य स्ट्रिंग के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | SVG छवि का नाम। यह null, खाली या whitespace नहीं हो सकता। |
|
|  | सामग्री | java.lang.String | सामग्री एक सामान्य स्ट्रिंग के रूप में, जिसमें SVG छवि की वैध XML‑अनुपालन सामग्री होती है। यह null, खाली या whitespace नहीं हो सकता। यदि यह SVG सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


सामग्री से नया SvgImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | SVG छवि का नाम। यह null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


जाँच करता है कि निर्दिष्ट टेक्स्टुअल XML-अनुपालन सामग्री सतह पर सत्यापित हो
एक SVG इमेज को दर्शाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | सामग्री | java.lang.String | SVG छवि की XML सामग्री को साधारण टेक्स्ट के रूप में, बेस64‑एन्कोडेड सामग्री नहीं |
|

**Returns:**
बूलियन - यदि निर्दिष्ट स्ट्रिंग को पहली नज़र में वैध SVG माना जा सकता है तो True, यदि निश्चित रूप से SVG नहीं है तो false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Svg लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


इस SVG छवि की सामग्री को बाइनरी स्ट्रीम के रूप में लौटाता है


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


इस SVG छवि की सामग्री को साधारण टेक्स्ट (XML प्रारूप में) के रूप में लौटाता है


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


इस SVG छवि की सामग्री को उसके मूल XML‑अनुपालन रूप में लौटाता है
पाठ्य रूप


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


इस SVG छवि को फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे इस SVG छवि की सामग्री के साथ बनाया जाएगा (यदि मौजूद नहीं है) या अधिलेखित किया जाएगा (यदि मौजूद है) |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


इस वेक्टर SVG छवि को रास्टर PNG छवि में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | आउटपुट स्ट्रीम, जिसमें PNG इमेज की सामग्री लिखी जाएगी। NULL नहीं हो सकता और लिखने योग्य होना चाहिए। |
|

### dispose() {#dispose--}
```
public void dispose()
```


इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स को
और प्रॉपर्टीज़ काम नहीं कर रही हैं


