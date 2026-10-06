---
title: "TtfFont"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "TTF TrueType Font फ़ॉर्मेट में एक फ़ॉन्ट का प्रतिनिधित्व करता है"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

TTF (ट्रू टाइप फ़ॉन्ट) फ़ॉर्मेट में एक फ़ॉन्ट को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | सामग्री से, जो base64-encoded है, नया TtfFont क्लास बनाता है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | सामग्री से, जो बाइट स्ट्रीम है, नया TtfFont क्लास बनाता है, और |
निर्दिष्ट नाम के साथ
|
## Fields

| Field | विवरण |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTF हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध TTF फ़ॉन्ट है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध TTF फ़ॉन्ट है या नहीं |
|
|  | [getType()](#getType--) | FontType.Ttf लौटाता है |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


सामग्री से, जो base64-encoded है, नया TtfFont क्लास बनाता है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | TTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री base64-encoded स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह TTF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


सामग्री से, जो बाइट स्ट्रीम है, नया TtfFont क्लास बनाता है, और
निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | TTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTF हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध TTF फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जो संभवतः एक TTF संसाधन रखती है |
|

**Returns:**
बूलियन - True यदि निर्दिष्ट स्ट्रीम में वैध TTF फ़ॉन्ट है, false अन्यथा

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-encoded स्ट्रिंग वैध TTF फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः TTF फ़ॉन्ट की सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
बूलियन - True यदि निर्दिष्ट स्ट्रिंग में वैध TTF फ़ॉन्ट है, false अन्यथा

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttf लौटाता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
