---
title: "TextResourceBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "टेक्स्ट सामग्री और एन्कोडिंग वाले किसी भी समर्थित टेक्स्ट संसाधन के लिए बेस क्लास।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

टेक्स्ट सामग्री और एन्कोडिंग वाले किसी भी समर्थित टेक्स्ट संसाधन के लिए बेस क्लास।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | निर्दिष्ट पाठ सामग्री और एन्कोडिंग से नया टेक्स्ट रिसोर्स बनाता है |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | निर्दिष्ट बाइट स्ट्रीम और एन्कोडिंग से नया टेक्स्ट रिसोर्स बनाता है |
|
## Fields

| Field | विवरण |
| --- | --- |
| [Disposed](#Disposed) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | फ़ाइल एक्सटेंशन के बिना इस टेक्स्ट रिसोर्स का नाम लौटाता है |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | इस टेक्स्ट रिसोर्स का सही फ़ाइलनाम लौटाता है, जो नाम से बना होता है |
और extension
|
|  | [getEncoding()](#getEncoding--) | इस टेक्स्टुअल रिसोर्स की एन्कोडिंग लौटाता है। |
|
|  | [getByteContent()](#getByteContent--) | मूल के साथ बाइट स्ट्रीम के रूप में इस टेक्स्ट रिसोर्स की सामग्री लौटाता है। |
एन्कोडिंग
|
|  | [getTextContent()](#getTextContent--) | इस टेक्स्ट संसाधन की सामग्री को एक मानक स्ट्रिंग के रूप में लौटाता है |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस टेक्स्ट संसाधन को निर्दिष्ट फ़ाइल में सहेजता है |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | इस इंस्टेंस की समानता को निर्दिष्ट मान के साथ जांचता है। |
|
|  | [dispose()](#dispose--) | इस टेक्स्ट संसाधन को नष्ट करता है, उसकी सामग्री को नष्ट करते हुए और अधिकांश |
मेथड्स और प्रॉपर्टीज़ को अकार्यशील बनाता है।
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह टेक्स्ट संसाधन नष्ट हुआ है या नहीं |
|
|  | [getType()](#getType--) | इम्प्लीमेंटिंग टाइप को टेक्स्ट के प्रकार की जानकारी लौटानी चाहिए |
संसाधन
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


निर्दिष्ट पाठ सामग्री और एन्कोडिंग से नया टेक्स्ट रिसोर्स बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | संसाधन का अनिवार्य नाम, जो उसके अद्वितीय पहचानकर्ता के रूप में कार्य करता है। आमतौर पर यह फ़ाइल नाम होता है। |
|
|  | textualContent | java.lang.String | संसाधन की टेक्स्टुअल सामग्री, NULL या खाली नहीं हो सकती |
|
|  | originalEncoding | java.nio.charset.Charset | संसाधन का मूल एन्कोडिंग, NULL या खाली नहीं हो सकता |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


निर्दिष्ट बाइट स्ट्रीम और एन्कोडिंग से नया टेक्स्ट रिसोर्स बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | संसाधन का अनिवार्य नाम, जो उसके अद्वितीय पहचानकर्ता के रूप में कार्य करता है। आमतौर पर यह फ़ाइल नाम होता है। |
|
|  | binaryContent | java.io.InputStream | संसाधन की बाइनरी सामग्री बाइट स्ट्रीम के रूप में। NULL नहीं हो सकता, नष्ट नहीं होना चाहिए, पढ़ने योग्य और खोज योग्य होना चाहिए। |
|
|  | originalEncoding | java.nio.charset.Charset | संसाधन का मूल एन्कोडिंग, NULL या खाली नहीं हो सकता |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


फ़ाइल एक्सटेंशन के बिना इस टेक्स्ट रिसोर्स का नाम लौटाता है


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


इस टेक्स्ट रिसोर्स का सही फ़ाइलनाम लौटाता है, जो नाम से बना होता है
और extension


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


इस टेक्स्टुअल संसाधन का एन्कोडिंग लौटाता है। आमतौर पर UTF-8 लौटाता है।


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


मूल के साथ बाइट स्ट्रीम के रूप में इस टेक्स्ट रिसोर्स की सामग्री लौटाता है।
एन्कोडिंग


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


इस टेक्स्ट संसाधन की सामग्री को एक मानक स्ट्रिंग के रूप में लौटाता है


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


इस टेक्स्ट संसाधन को निर्दिष्ट फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जो यदि पहले से मौजूद है तो बनाया या पुनः लिखा जाएगा |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


इस इंस्टेंस की समानता को निर्दिष्ट मान के साथ जांचता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | अज्ञात प्रकार का अन्य HTML संसाधन, जो संभावित रूप से TextResourceBase का उत्तराधिकारी भी है |
|

**Returns:**
boolean - यदि समान हों तो true लौटाता है, या यदि असमान हों तो false लौटाता है

### dispose() {#dispose--}
```
public final void dispose()
```


इस टेक्स्ट संसाधन को नष्ट करता है, उसकी सामग्री को नष्ट करते हुए और अधिकांश
मेथड्स और प्रॉपर्टीज़ अकार्यशील। कई कॉल्स को सहनशील।


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


निर्धारित करता है कि यह टेक्स्ट संसाधन नष्ट हुआ है या नहीं


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


इम्प्लीमेंटिंग टाइप को टेक्स्ट के प्रकार की जानकारी लौटानी चाहिए
संसाधन


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
