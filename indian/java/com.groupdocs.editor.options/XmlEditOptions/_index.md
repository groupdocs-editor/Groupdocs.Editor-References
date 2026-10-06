---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "XML eXtensible Markup Language दस्तावेज़ों को लोड करने और उन्हें HTML में परिवर्तित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 51
url: /hi/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

XML (eXtensible Markup Language) को लोड करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
दस्तावेज़ों को और उन्हें HTML में परिवर्तित करने के लिए

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
खोलना।
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
खोलना।
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | क्षतिग्रस्त XML संरचना को ठीक करने के तंत्र को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | क्षतिग्रस्त XML संरचना को ठीक करने के तंत्र को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | URI पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है। |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | URI पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है। |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | गुण में ईमेल पते की पहचान के एल्गोरिदम को सक्षम करने की अनुमति देता है। |
मान
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | गुण में ईमेल पते की पहचान के एल्गोरिदम को सक्षम करने की अनुमति देता है। |
मान
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | आंतरिक टैग में अंत के व्हाइटस्पेस को ट्रंकेट करने को सक्षम करने की अनुमति देता है। |
पाठ।
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | आंतरिक टैग में अंत के व्हाइटस्पेस को ट्रंकेट करने को सक्षम करने की अनुमति देता है। |
पाठ।
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | गुण मानों के लिए उद्धरण प्रकार (एकल या दोहरा) निर्दिष्ट करने की अनुमति देता है। |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | गुण मानों के लिए उद्धरण प्रकार (एकल या दोहरा) निर्दिष्ट करने की अनुमति देता है। |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | HTML में प्रदर्शित होने पर XML संरचना पर लागू होने वाले XML हाइलाइटिंग को समायोजित करने की अनुमति देता है। |
|
|  | [getFormatOptions()](#getFormatOptions--) | HTML में प्रदर्शित होने पर XML संरचना पर लागू होने वाले XML फ़ॉर्मेटिंग को समायोजित करने की अनुमति देता है। |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
खोलना। डिफ़ॉल्ट रूप से null \\u2014 आंतरिक दस्तावेज़ एन्कोडिंग लागू होगी।


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
खोलना। डिफ़ॉल्ट रूप से null \\u2014 आंतरिक दस्तावेज़ एन्कोडिंग लागू होगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


क्षतिग्रस्त XML संरचना को ठीक करने के तंत्र को सक्षम या अक्षम करने की अनुमति देता है।
डिफ़ॉल्ट रूप से अक्षम (false) है।

*** ** * ** ***


डिफ़ॉल्ट रूप से केवल उचित मान्य सही-फ़ॉर्मेटेड XML दस्तावेज़ होते हैं
स्वीकार्य। जब यह विकल्प सक्षम किया जाता है, GroupDocs.Editor ठीक करने का प्रयास करेगा
यदि संभव हो तो क्षतिग्रस्त XML संरचना को।


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


क्षतिग्रस्त XML संरचना को ठीक करने के तंत्र को सक्षम या अक्षम करने की अनुमति देता है।
डिफ़ॉल्ट रूप से अक्षम (false) है।

*** ** * ** ***


डिफ़ॉल्ट रूप से केवल उचित मान्य सही-फ़ॉर्मेटेड XML दस्तावेज़ होते हैं
स्वीकार्य। जब यह विकल्प सक्षम किया जाता है, GroupDocs.Editor ठीक करने का प्रयास करेगा
यदि संभव हो तो क्षतिग्रस्त XML संरचना को।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


URI पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है।


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


URI पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


गुण में ईमेल पते की पहचान के एल्गोरिदम को सक्षम करने की अनुमति देता है।
मान


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


गुण में ईमेल पते की पहचान के एल्गोरिदम को सक्षम करने की अनुमति देता है।
मान


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


आंतरिक टैग में अंत के व्हाइटस्पेस को ट्रंकेट करने को सक्षम करने की अनुमति देता है।
पाठ। डिफ़ॉल्ट रूप से अक्षम (false) \\u2014 अंत के व्हाइटस्पेस होंगे
संरक्षित।


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


आंतरिक टैग में अंत के व्हाइटस्पेस को ट्रंकेट करने को सक्षम करने की अनुमति देता है।
पाठ। डिफ़ॉल्ट रूप से अक्षम (false) \\u2014 अंत के व्हाइटस्पेस होंगे
संरक्षित।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


गुण मानों के लिए उद्धरण प्रकार (एकल या दोहरा) निर्दिष्ट करने की अनुमति देता है। दोहरे उद्धरण डिफ़ॉल्ट हैं।


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


गुण मानों के लिए उद्धरण प्रकार (एकल या दोहरा) निर्दिष्ट करने की अनुमति देता है। दोहरे उद्धरण डिफ़ॉल्ट हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


HTML में प्रदर्शित होने पर XML संरचना पर लागू होने वाले XML हाइलाइटिंग को समायोजित करने की अनुमति देता है। डिफ़ॉल्ट हाइलाइटिंग उपयोग की जाती है और समायोज्य है। null नहीं हो सकता।


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


HTML में प्रदर्शित होने पर XML संरचना पर लागू होने वाले XML फ़ॉर्मेटिंग को समायोजित करने की अनुमति देता है। डिफ़ॉल्ट फ़ॉर्मेटिंग उपयोग की जाती है और समायोज्य है। null नहीं हो सकता।


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
