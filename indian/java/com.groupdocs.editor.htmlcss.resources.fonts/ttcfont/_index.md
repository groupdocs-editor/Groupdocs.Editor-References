---
title: "TtcFont"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "TTC TrueType Collection प्रारूप में एक फ़ॉन्ट का प्रतिनिधित्व करता है"
type: docs
weight: 14
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

TTC (ट्रू टाइप कलेक्शन) फ़ॉर्मेट में एक फ़ॉन्ट को दर्शाता है।


और देखें: https://docs.fileformat.com/font/ttc/

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | सामग्री से नई TtcFont क्लास बनाता है, जो base64-एन्कोडेड के रूप में प्रस्तुत है |
स्ट्रिंग, और निर्दिष्ट नाम के साथ
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | सामग्री से नई TtcFont क्लास बनाता है, जो बाइट स्ट्रीम के रूप में प्रस्तुत है, और |
निर्दिष्ट नाम के साथ
|
## Fields

| Field | विवरण |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध TTC फ़ॉन्ट है या नहीं |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध TTC फ़ॉन्ट है या नहीं |
|
|  | [getType()](#getType--) | FontType.Ttc लौटाता है |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC हेडर संस्करण, "1" या "2" हो सकता है |
|
|  | [getFontsNumber()](#getFontsNumber--) | इस TTC में फ़ॉन्टों की संख्या |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | बताता है कि इस TTC में DSIG तालिका है या नहीं। |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


सामग्री से नई TtcFont क्लास बनाता है, जो base64-एन्कोडेड के रूप में प्रस्तुत है
स्ट्रिंग, और निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | TTC फ़ॉन्ट का नाम। यह null, खाली या व्हाइटस्पेस नहीं हो सकता। |
|
|  | contentInBase64 | java.lang.String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। यह null, खाली या व्हाइटस्पेस नहीं हो सकता। यदि यह TTC सामग्री नहीं है, तो अपवाद फेंका जाएगा। |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


सामग्री से नई TtcFont क्लास बनाता है, जो बाइट स्ट्रीम के रूप में प्रस्तुत है, और
निर्दिष्ट नाम के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | TTC फ़ॉन्ट का नाम। यह null, खाली या व्हाइटस्पेस नहीं हो सकता। |
|
|  | binaryContent | java.io.InputStream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध TTC फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | बाइट स्ट्रीम, जो संभवतः एक TTC संसाधन रखती है |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम में वैध TTC फ़ॉन्ट है तो True, अन्यथा false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध TTC फ़ॉन्ट है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | संभवतः TTC फ़ॉन्ट की सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रिंग में वैध TTC फ़ॉन्ट है तो True, अन्यथा false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttc लौटाता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC हेडर संस्करण, "1" या "2" हो सकता है


**Returns:**
बाइट
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


इस TTC में फ़ॉन्टों की संख्या


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


बताता है कि इस TTC में DSIG तालिका है या नहीं। DSIG तालिका मौजूद हो सकती है
केवल यदि TTC का हेडर संस्करण 2.0 है।


**Returns:**
boolean
