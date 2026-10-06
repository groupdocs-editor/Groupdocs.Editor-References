---
title: "WmfImage"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "WMF Windows MetaFile फ़ॉर्मेट में एक वेक्टर इमेज को उसके मेटाडेटा और अतिरिक्त मेथड्स के साथ दर्शाता है"
type: docs
weight: 14
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

WMF (Windows MetaFile) फ़ॉर्मेट में एक वेक्टर इमेज को उसके साथ दर्शाता है
मेटाडेटा और अतिरिक्त मेथड्स

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | सामग्री से नया WmfImage इंस्टेंस बनाता है, जो base64-एन्कोडेड के रूप में दर्शाया गया है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | सामग्री से नया WmfImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, |
और निर्दिष्ट नाम के साथ
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध WMF इमेज है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध WMF इमेज है या नहीं |
|
|  | [getType()](#getType--) | ImageType.Wmf लौटाता है |
|
|  | [getByteContent()](#getByteContent--) | इस WMF इमेज की सामग्री को बाइनरी स्ट्रीम के रूप में लौटाता है |
|
|  | [getTextContent()](#getTextContent--) | इस WMF इमेज की सामग्री को साधारण टेक्स्ट के रूप में लौटाता है |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस WMF इमेज को फ़ाइल में सहेजता है |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | इस वेक्टर WMF इमेज को रास्टर PNG इमेज में सहेजता है |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | इस वेक्टर WMF इमेज को वेक्टर SVG इमेज में सहेजता है |
|
|  | [dispose()](#dispose--) | इस WMF इमेज को उसके कंटेंट को डिस्पोज करके और अधिकांश इसे |
मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


सामग्री से नया WmfImage इंस्टेंस बनाता है, जो base64-एन्कोडेड के रूप में दर्शाया गया है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | WMF इमेज का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह WMF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


सामग्री से नया WmfImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है,
और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | WMF इमेज का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध WMF इमेज है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | इनपुट बाइट स्ट्रीम। NULL नहीं हो सकता, पढ़ने और सीकिंग का समर्थन करना चाहिए। |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम वैध WMF इमेज रखती है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध WMF इमेज है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | इनपुट स्ट्रिंग, जहाँ WMF इमेज की सामग्री base64 एन्कोडिंग में संग्रहीत है। NULL या खाली नहीं हो सकता। |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग वैध WMF इमेज रखती है तो True, अन्यथा false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Wmf लौटाता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


इस WMF इमेज की सामग्री को बाइनरी स्ट्रीम के रूप में लौटाता है


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


इस WMF इमेज की सामग्री को साधारण टेक्स्ट के रूप में लौटाता है


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


इस WMF इमेज को फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे इस WMF इमेज की सामग्री के साथ बनाया जाएगा (यदि नहीं है) या अधिलेखित किया जाएगा (यदि मौजूद है) |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


इस वेक्टर WMF इमेज को रास्टर PNG इमेज में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | आउटपुट स्ट्रीम, जिसमें PNG इमेज की सामग्री लिखी जाएगी। NULL नहीं हो सकता और लिखने योग्य होना चाहिए। |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


इस वेक्टर WMF इमेज को वेक्टर SVG इमेज में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | आउटपुट स्ट्रीम, जिसमें SVG इमेज की सामग्री लिखी जाएगी। NULL नहीं हो सकता और लिखने योग्य होना चाहिए। |
|

### dispose() {#dispose--}
```
public void dispose()
```


इस WMF इमेज को उसके कंटेंट को डिस्पोज करके और अधिकांश इसे
मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है


