---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सादा टेक्स्ट TXT दस्तावेज़ लोड करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 39
url: /hi/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

सादा टेक्स्ट (TXT) दस्तावेज़ लोड करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
खोलने पर
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
खोलने पर
|
|  | [getRecognizeLists()](#getRecognizeLists--) | जब दस्तावेज़ है तो क्रमांकित सूची आइटम कैसे पहचाने जाते हैं, इसे निर्दिष्ट करने की अनुमति देता है |
सादा टेक्स्ट फ़ॉर्मेट से आयातित।
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | जब दस्तावेज़ है तो क्रमांकित सूची आइटम कैसे पहचाने जाते हैं, इसे निर्दिष्ट करने की अनुमति देता है |
सादा टेक्स्ट फ़ॉर्मेट से आयातित।
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | लीडिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | लीडिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | ट्रेलिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | ट्रेलिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। |
|
|  | [getEnablePagination()](#getEnablePagination--) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [getDirection()](#getDirection--) | इनपुट सादा टेक्स्ट में टेक्स्ट प्रवाह की दिशा निर्दिष्ट करने की अनुमति देता है |
दस्तावेज़।
|
|  | [setDirection(int value)](#setDirection-int-) | इनपुट सादा टेक्स्ट में टेक्स्ट प्रवाह की दिशा निर्दिष्ट करने की अनुमति देता है |
दस्तावेज़।
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
खोलने पर


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
खोलने पर


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


जब दस्तावेज़ है तो क्रमांकित सूची आइटम कैसे पहचाने जाते हैं, इसे निर्दिष्ट करने की अनुमति देता है
सादा टेक्स्ट फ़ॉर्मेट से आयातित। डिफ़ॉल्ट मान true है।


*** ** * ** ***

यदि यह विकल्प false पर सेट किया जाता है, तो सूची पहचान एल्गोरिद्म सूची पैराग्राफ़ का पता लगाता है, जब सूची संख्याएँ डॉट, राइट ब्रैकेट या बुलेट प्रतीकों (जैसे \"\\\\u2022\", \"\\*\", \"-\" या \"o\") में समाप्त होती हैं। यदि यह विकल्प true पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या विभाजक के रूप में उपयोग होते हैं: अरबी शैली की क्रमांकन (1., 1.1.2.) के लिए सूची पहचान एल्गोरिद्म व्हाइटस्पेस और डॉट (\".\") दोनों प्रतीकों का उपयोग करता है।

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


जब दस्तावेज़ है तो क्रमांकित सूची आइटम कैसे पहचाने जाते हैं, इसे निर्दिष्ट करने की अनुमति देता है
सादा टेक्स्ट फ़ॉर्मेट से आयातित। डिफ़ॉल्ट मान true है।


*** ** * ** ***

यदि यह विकल्प false पर सेट किया जाता है, तो सूची पहचान एल्गोरिद्म सूची पैराग्राफ़ का पता लगाता है, जब सूची संख्याएँ डॉट, राइट ब्रैकेट या बुलेट प्रतीकों (जैसे \"\\\\u2022\", \"\\*\", \"-\" या \"o\") में समाप्त होती हैं। यदि यह विकल्प true पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या विभाजक के रूप में उपयोग होते हैं: अरबी शैली की क्रमांकन (1., 1.1.2.) के लिए सूची पहचान एल्गोरिद्म व्हाइटस्पेस और डॉट (\".\") दोनों प्रतीकों का उपयोग करता है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


लीडिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से
लीडिंग स्पेस को बाएँ इंडेंट में बदलता है।


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


लीडिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से
लीडिंग स्पेस को बाएँ इंडेंट में बदलता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


ट्रेलिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से
सभी ट्रेलिंग स्पेस को ट्रंकेट करता है।


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


ट्रेलिंग स्पेस हैंडलिंग के पसंदीदा विकल्प को प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से
सभी ट्रेलिंग स्पेस को ट्रंकेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट निष्क्रिय है (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट निष्क्रिय है (false).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


इनपुट सादा टेक्स्ट में टेक्स्ट प्रवाह की दिशा निर्दिष्ट करने की अनुमति देता है
दस्तावेज़। डिफ़ॉल्ट रूप से बाएँ‑से‑दाएँ है।


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


इनपुट सादा टेक्स्ट में टेक्स्ट प्रवाह की दिशा निर्दिष्ट करने की अनुमति देता है
दस्तावेज़। डिफ़ॉल्ट रूप से बाएँ‑से‑दाएँ है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

