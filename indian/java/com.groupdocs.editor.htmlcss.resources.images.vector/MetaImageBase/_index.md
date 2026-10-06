---
title: "MetaImageBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "WMF और EMF इमेज फ़ॉर्मेट्स के लिए बेस एब्स्ट्रैक्ट क्लास"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

WMF और EMF इमेज फ़ॉर्मेट्स के लिए बेस एब्स्ट्रैक्ट क्लास

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | सामान्य कंस्ट्रक्टर, जो WMF या EMF इंस्टेंस बनाने के लिए तैयार करता है |
base64-एन्कोडेड स्ट्रिंग
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | सामान्य कंस्ट्रक्टर, जो WMF या EMF इंस्टेंस बनाने के लिए तैयार करता है |
बाइट स्ट्रीम
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | निर्धारित करता है कि निर्दिष्ट बाइट स्ट्रीम में वैध WMF छवि है या नहीं |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में वैध WMF छवि है या नहीं, जो है |
base64 के साथ एन्कोडेड
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | निर्धारित करता है कि निर्दिष्ट बाइट स्ट्रीम में वैध EMF छवि है या नहीं |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में वैध EMF छवि है या नहीं, जो है |
base64 के साथ एन्कोडेड
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | इम्प्लीमेंटिंग प्रकार को वर्तमान वेक्टर मेटा-इमेज को यहाँ सहेजना चाहिए |
वेक्टर SVG फ़ॉर्मेट को निर्दिष्ट बाइट स्ट्रीम में
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


सामान्य कंस्ट्रक्टर, जो WMF या EMF इंस्टेंस बनाने के लिए तैयार करता है
base64-एन्कोडेड स्ट्रिंग


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | अनिवार्य नाम |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64 स्ट्रिंग के रूप में। यह NULL या खाली नहीं होना चाहिए। |
|
|  | isWmf | boolean | WMF के लिए true, EMF के लिए false |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


सामान्य कंस्ट्रक्टर, जो WMF या EMF इंस्टेंस बनाने के लिए तैयार करता है
बाइट स्ट्रीम


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | अनिवार्य नाम |
|
|  | binaryContent | java.io.InputStream | सामग्री को बाइट स्ट्रीम के रूप में। यह वैध होना चाहिए। |
|
|  | isWmf | boolean | WMF के लिए true, EMF के लिए false |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


निर्धारित करता है कि निर्दिष्ट बाइट स्ट्रीम में वैध WMF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | इनपुट बाइट स्ट्रीम। यह वैध होना चाहिए। |
|

**Returns:**
boolean - यदि वैध हो तो 'true' और यदि अमान्य हो तो 'false' लौटाता है

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में वैध WMF छवि है या नहीं, जो है
base64 के साथ एन्कोडेड


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | स्ट्रिंग, जिसमें मान लिया गया है कि एक base64-एन्कोडेड WMF छवि है |
|

**Returns:**
boolean - यदि वैध हो तो 'true' और यदि अमान्य हो तो 'false' लौटाता है

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


निर्धारित करता है कि निर्दिष्ट बाइट स्ट्रीम में वैध EMF छवि है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | इनपुट बाइट स्ट्रीम। यह वैध होना चाहिए। |
|

**Returns:**
boolean - यदि वैध हो तो 'true' और यदि अमान्य हो तो 'false' लौटाता है

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


निर्धारित करता है कि निर्दिष्ट स्ट्रिंग में वैध EMF छवि है या नहीं, जो है
base64 के साथ एन्कोडेड


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, जिसे बेस64-एन्कोडेड EMF इमेज रखने के रूप में माना गया है |
|

**Returns:**
boolean - यदि वैध हो तो 'true' और यदि अमान्य हो तो 'false' लौटाता है

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


इम्प्लीमेंटिंग प्रकार को वर्तमान वेक्टर मेटा-इमेज को यहाँ सहेजना चाहिए
वेक्टर SVG फ़ॉर्मेट को निर्दिष्ट बाइट स्ट्रीम में


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | बाइट स्ट्रीम, जिसमें इस वेक्टर मेटा-इमेज का SVG संस्करण संग्रहीत किया जाएगा। NULL नहीं होना चाहिए और लिखने का समर्थन करना चाहिए। |
|

