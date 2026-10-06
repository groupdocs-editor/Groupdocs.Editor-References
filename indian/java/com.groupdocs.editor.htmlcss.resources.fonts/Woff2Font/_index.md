---
title: "Woff2Font"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "WOFF2 Web Open Font Format फ़ॉर्मेट में एक फ़ॉन्ट का प्रतिनिधित्व करता है"
type: docs
weight: 16
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

WOFF2 (वेब ओपन फ़ॉन्ट फ़ॉर्मेट) फ़ॉर्मेट में एक फ़ॉन्ट को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | सामग्री से, जो base64-encoded है, नया Woff2Font क्लास बनाता है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | सामग्री से, जो बाइट स्ट्रीम है, नया Woff2Font क्लास बनाता है, और |
निर्दिष्ट नाम के साथ
|
## Fields

| Field | विवरण |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2 हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध WOFF2 फ़ॉन्ट है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध WOFF2 फ़ॉन्ट है या नहीं |
|
|  | [getType()](#getType--) | FontType.Woff2 लौटाता है |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


सामग्री से, जो base64-encoded है, नया Woff2Font क्लास बनाता है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | WOFF2 फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री base64-encoded स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह WOFF2 सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


सामग्री से, जो बाइट स्ट्रीम है, नया Woff2Font क्लास बनाता है, और
निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | WOFF2 फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट किया जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2 हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध WOFF2 फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जो संभवतः एक WOFF2 संसाधन रखती है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम वैध WOFF2 फ़ॉन्ट रखती है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध WOFF2 फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः WOFF2 फ़ॉन्ट की सामग्री base64-encoded स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग वैध WOFF2 फ़ॉन्ट रखती है तो True, अन्यथा false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff2 लौटाता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
