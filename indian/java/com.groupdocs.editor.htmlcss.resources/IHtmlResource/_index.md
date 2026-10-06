---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "अज्ञात HTML संसाधन (रास्टर या वेक्टर इमेज, स्टाइलशीट, फ़ॉन्ट, टेक्स्ट संसाधन, CSS, XML आदि) का एक इंस्टेंस दर्शाता है"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

अज्ञात HTML संसाधन (रास्टर या वेक्टर इमेज,
स्टाइलशीट, फ़ॉन्ट, टेक्स्ट संसाधन (CSS, XML) आदि)

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | HTML संसाधन का नाम |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | निर्दिष्ट संसाधन की उपयुक्त फ़ाइल के साथ सही फ़ाइलनाम |
एक्सटेंशन
|
|  | [getType()](#getType--) | HTML संसाधन का प्रकार |
|
|  | [getByteContent()](#getByteContent--) | HTML संसाधन की सामग्री बाइट स्ट्रीम के रूप में |
|
|  | [getTextContent()](#getTextContent--) | HTML संसाधन की सामग्री base64-एन्कोडेड टेक्स्ट स्ट्रिंग के रूप में |
बाइनरी संसाधनों के लिए या टेक्स्टुअल संसाधनों के लिए साधारण टेक्स्ट
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | वर्तमान संसाधन को निर्दिष्ट फ़ाइल में सहेजता है |
|
### getName() {#getName--}
```
public abstract String getName()
```


HTML संसाधन का नाम


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


निर्दिष्ट संसाधन की उपयुक्त फ़ाइल के साथ सही फ़ाइलनाम
एक्सटेंशन


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


HTML संसाधन का प्रकार


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


HTML संसाधन की सामग्री बाइट स्ट्रीम के रूप में


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


HTML संसाधन की सामग्री base64-एन्कोडेड टेक्स्ट स्ट्रिंग के रूप में
बाइनरी संसाधनों के लिए या टेक्स्टुअल संसाधनों के लिए साधारण टेक्स्ट


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


वर्तमान संसाधन को निर्दिष्ट फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे वर्तमान संसाधन की सामग्री के साथ बनाया या पुनर्लिखित किया जाएगा |
|

