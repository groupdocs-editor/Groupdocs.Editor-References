---
title: "OtfFont"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "OTF Open Type Format प्रारूप में एक फ़ॉन्ट का प्रतिनिधित्व करता है"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

OTF (ओपन टाइप फ़ॉर्मेट) फ़ॉर्मेट में एक फ़ॉन्ट को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | base64-encoded के रूप में प्रतिनिधित्व की गई सामग्री से नया OtfFont वर्ग बनाता है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | बाइट स्ट्रीम के रूप में प्रतिनिधित्व की गई सामग्री से नया OtfFont वर्ग बनाता है, और |
निर्दिष्ट नाम के साथ
|
## Fields

| Field | विवरण |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | OTF हेडर आकार (बाइट्स में), जो इसकी मान्यकरण के लिए आवश्यक है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध OTF फ़ॉन्ट है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध OTF फ़ॉन्ट है या नहीं |
|
|  | [getType()](#getType--) | वापस देता है |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


base64-encoded के रूप में प्रतिनिधित्व की गई सामग्री से नया OtfFont वर्ग बनाता है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | OTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-encoded स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह OTF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


बाइट स्ट्रीम के रूप में प्रतिनिधित्व की गई सामग्री से नया OtfFont वर्ग बनाता है, और
निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | OTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


OTF हेडर आकार (बाइट्स में), जो इसकी मान्यकरण के लिए आवश्यक है


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध OTF फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जिसमें संभवतः OTF संसाधन हो सकता है |
|

**Returns:**
boolean - true यदि निर्दिष्ट स्ट्रीम वैध OTF फ़ॉन्ट रखती है, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध OTF फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः OTF फ़ॉन्ट की सामग्री base64-encoded स्ट्रिंग के रूप में |
|

**Returns:**
boolean - true यदि निर्दिष्ट स्ट्रिंग वैध OTF फ़ॉन्ट रखती है, अन्यथा false

### getType() {#getType--}
```
public FontType getType()
```


वापस देता है
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
