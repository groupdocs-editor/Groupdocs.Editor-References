---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी स्वरूप के एक ऑडियो संसाधन को दर्शाता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

किसी भी स्वरूप के एक ऑडियो संसाधन को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | MP3 सामग्री, जो बाइट स्ट्रीम के रूप में प्रतिनिधित्व करती है, और निर्दिष्ट नाम के साथ नया Mp3Audio क्लास बनाता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध MP3 सामग्री है या नहीं |
|
|  | [getName()](#getName--) | इस MP3 सामग्री का नाम लौटाता है। |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | इस MP3 सामग्री का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। |
|
|  | [getType()](#getType--) | एक AudioFormat.Mp3 लौटाता है (साथ ही covariant return के माध्यम से IHtmlResource.getFormat() को भी संतुष्ट करता है) |
|
|  | [getByteContent()](#getByteContent--) | इस फ़ॉन्ट की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | इस MP3 ऑडियो संसाधन की सामग्री को मूल स्थिति के साथ बाइट स्ट्रीम के रूप में लौटाता है |
|
|  | [getTextContent()](#getTextContent--) | इस MP3 संसाधन की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है। |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस MP3 संसाधन को निर्दिष्ट फ़ाइल में सहेजता है |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट HTML संसाधन के साथ जाँच करता है |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट फ़ॉन्ट संसाधन के साथ जाँच करता है |
|
|  | [dispose()](#dispose--) | इस MP3 संसाधन को नष्ट करता है, उसकी सामग्री को नष्ट करके अधिकांश मेथड और प्रॉपर्टी को अकार्यशील बना देता है। |
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह MP3 सामग्री नष्ट हुई है या नहीं। |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


MP3 सामग्री, जो बाइट स्ट्रीम के रूप में प्रतिनिधित्व करती है, और निर्दिष्ट नाम के साथ नया Mp3Audio क्लास बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | MP3 सामग्री का नाम। null, खाली या whitespace नहीं हो सकता। |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | सामग्री बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और seekable होना चाहिए। यदि यह इंस्टेंस नष्ट हो जाएगा, तो यह स्ट्रीम भी नष्ट हो जाएगी। |
|
|  | leaveOpen | boolean | निर्धारित करता है कि Mp3Audio इंस्टेंस नष्ट होने पर निर्दिष्ट स्ट्रीम को नष्ट किया जाए या नहीं। |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


जाँचता है कि निर्दिष्ट स्ट्रीम वैध MP3 सामग्री है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | बाइट स्ट्रीम, जिसमें संभवतः MP3 सामग्री हो। |
|

**Returns:**
boolean - यदि निर्दिष्ट स्ट्रीम वैध MP3 सामग्री रखती है तो True, अन्यथा false।

### getName() {#getName--}
```
public String getName()
```


इस MP3 सामग्री का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः फ़ाइलनाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


इस MP3 सामग्री का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से मिलकर बनता है। सिद्धांततः यह नाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


एक AudioFormat.Mp3 लौटाता है (साथ ही covariant return के माध्यम से IHtmlResource.getFormat() को भी संतुष्ट करता है)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


इस फ़ॉन्ट की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


इस MP3 ऑडियो संसाधन की सामग्री को मूल स्थिति के साथ बाइट स्ट्रीम के रूप में लौटाता है


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


इस MP3 संसाधन की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है। यह मान पहली बार कॉल करने के बाद कैश किया जाता है।


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


इस MP3 संसाधन को निर्दिष्ट फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे बनाया या पुनः लिखा जाएगा। |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट HTML संसाधन के साथ जाँच करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource इंटरफ़ेस का अन्य उत्तराधिकारी। |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


संदर्भ समानता के आधार पर इस इंस्टेंस की निर्दिष्ट फ़ॉन्ट संसाधन के साथ जाँच करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Mp3Audio क्लास का अन्य इंस्टेंस। |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### dispose() {#dispose--}
```
public void dispose()
```


इस MP3 संसाधन को नष्ट करता है, उसकी सामग्री को नष्ट करके अधिकांश मेथड और प्रॉपर्टी को अकार्यशील बना देता है।


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


निर्धारित करता है कि यह MP3 सामग्री नष्ट हुई है या नहीं।


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

