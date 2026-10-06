---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "HTML दस्तावेज़ के लिए संसाधन के रूप में किसी भी समर्थित फ़ॉन्ट प्रकार की बेस क्लास, जिसमें सभी गुण शामिल हैं"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

HTML दस्तावेज़ के लिए संसाधन के रूप में किसी भी समर्थित फ़ॉन्ट प्रकार की बेस क्लास
सभी गुणों के साथ

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [Disposed](#Disposed) | इवेंट, जो तब होता है जब यह फ़ॉन्ट डिस्पोज़ किया जाता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | इस फ़ॉन्ट संसाधन का नाम लौटाता है। |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | इस फ़ॉन्ट संसाधन का सही फ़ाइलनाम लौटाता है, जो नाम से बना होता है |
और एक्सटेंशन।
|
|  | [getByteContent()](#getByteContent--) | इस फ़ॉन्ट की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है |
|
|  | [getTextContent()](#getTextContent--) | इस फ़ॉन्ट की सामग्री को base64-encoded स्ट्रिंग के रूप में लौटाता है। |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस फ़ॉन्ट को निर्दिष्ट फ़ाइल में सहेजता है |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट HTML संसाधन के साथ जाँच करता है |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट फ़ॉन्ट संसाधन के साथ जाँच करता है |
|
|  | [dispose()](#dispose--) | इस फ़ॉन्ट संसाधन को डिस्पोज़ करता है, इसकी सामग्री को डिस्पोज़ करता है और अधिकांश |
मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह फ़ॉन्ट डिस्पोज़ किया गया है या नहीं |
|
|  | [getType()](#getType--) | इम्प्लीमेंटिंग टाइप को विशिष्ट प्रकार की जानकारी लौटानी चाहिए |
फ़ॉन्ट संसाधन को विशिष्ट FontType टाइप के इंस्टेंस के रूप में, जो
सभी टाइप-विशिष्ट जानकारी को संलग्न करता है
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


इवेंट, जो तब होता है जब यह फ़ॉन्ट डिस्पोज़ किया जाता है


### getName() {#getName--}
```
public final String getName()
```


इस फ़ॉन्ट संसाधन का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम नहीं होता
एक्सटेंशन और सैद्धांतिक रूप से फ़ाइलनाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


इस फ़ॉन्ट संसाधन का सही फ़ाइलनाम लौटाता है, जो नाम से बना होता है
और एक्सटेंशन। सिद्धांततः यह नाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


इस फ़ॉन्ट की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


इस फ़ॉन्ट की सामग्री को base64-encoded स्ट्रिंग के रूप में लौटाता है। यह मान है
पहली बार कॉल करने के बाद कैश किया जाता है।


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


इस फ़ॉन्ट को निर्दिष्ट फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे बनाया या पुनः लिखा जाएगा। |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट HTML संसाधन के साथ जाँच करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource इंटरफ़ेस का अन्य उत्तराधिकारी। |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट फ़ॉन्ट संसाधन के साथ जाँच करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase सारभूत वर्ग का अन्य उत्तराधिकारी |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### dispose() {#dispose--}
```
public final void dispose()
```


इस फ़ॉन्ट संसाधन को डिस्पोज़ करता है, इसकी सामग्री को डिस्पोज़ करता है और अधिकांश
मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


निर्धारित करता है कि यह फ़ॉन्ट डिस्पोज़ किया गया है या नहीं


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


इम्प्लीमेंटिंग टाइप को विशिष्ट प्रकार की जानकारी लौटानी चाहिए
फ़ॉन्ट संसाधन को विशिष्ट FontType टाइप के इंस्टेंस के रूप में, जो
सभी टाइप-विशिष्ट जानकारी को संलग्न करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
