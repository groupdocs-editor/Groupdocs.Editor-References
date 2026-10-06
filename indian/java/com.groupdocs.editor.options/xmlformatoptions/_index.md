---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "विकल्प शामिल हैं जो XML दस्तावेज़ को HTML के रूप में प्रस्तुत करने पर उसके स्वरूपण को समायोजित करने की अनुमति देते हैं"
type: docs
weight: 52
url: /hi/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

जब XML दस्तावेज़ को HTML के रूप में दर्शाया जाता है, तो उसके फ़ॉर्मेटिंग को समायोजित करने की अनुमति देने वाले विकल्प शामिल हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | सक्षम होने पर, प्रत्येक XML तत्व में प्रत्येक विशेषता‑मान जोड़ी नई पंक्ति में रखी जाएगी। |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | सक्षम होने पर, प्रत्येक XML तत्व में प्रत्येक विशेषता‑मान जोड़ी नई पंक्ति में रखी जाएगी। |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | सक्षम होने पर, लीफ़ टेक्स्ट नोड्स (XML तत्वों के भीतर का पाठ्य सामग्री, जिसके कोई बच्चे नहीं होते) नई पंक्ति में बड़े बाएँ इंडेंट के साथ प्रदर्शित होंगे। |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | सक्षम होने पर, लीफ़ टेक्स्ट नोड्स (XML तत्वों के भीतर का पाठ्य सामग्री, जिसके कोई बच्चे नहीं होते) नई पंक्ति में बड़े बाएँ इंडेंट के साथ प्रदर्शित होंगे। |
|
|  | [getLeftIndent()](#getLeftIndent--) | प्रत्येक नई पंक्ति के बाएँ इंडेंट के लिए ऑफ़सेट निर्दिष्ट करने की अनुमति देता है। |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | प्रत्येक नई पंक्ति के बाएँ इंडेंट के लिए ऑफ़सेट निर्दिष्ट करने की अनुमति देता है। |
|
|  | [isDefault()](#isDefault--) | यह दर्शाता है कि इस XML स्वरूपण विकल्प के इस उदाहरण में डिफ़ॉल्ट मान है या नहीं |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


सक्षम होने पर, प्रत्येक XML तत्व में प्रत्येक विशेषता‑मान जोड़ी नई पंक्ति में रखी जाएगी।
डिफ़ॉल्ट रूप से यह false (अक्षम) — सभी विशेषता‑मान जोड़े एक ही पंक्ति में रखे जाते हैं।


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


सक्षम होने पर, प्रत्येक XML तत्व में प्रत्येक विशेषता‑मान जोड़ी नई पंक्ति में रखी जाएगी।
डिफ़ॉल्ट रूप से यह false (अक्षम) — सभी विशेषता‑मान जोड़े एक ही पंक्ति में रखे जाते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


सक्षम होने पर, लीफ़ टेक्स्ट नोड्स (XML तत्वों के भीतर का पाठ्य सामग्री, जिसके कोई बच्चे नहीं होते) नई पंक्ति में बड़े बाएँ इंडेंट के साथ प्रदर्शित होंगे।
डिफ़ॉल्ट रूप से यह false (अक्षम) — लीफ़ टेक्स्ट नोड्स को उनके पैरेंट के समान पंक्ति में रखा जाता है, बिना नए इंडेंट के।


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


सक्षम होने पर, लीफ़ टेक्स्ट नोड्स (XML तत्वों के भीतर का पाठ्य सामग्री, जिसके कोई बच्चे नहीं होते) नई पंक्ति में बड़े बाएँ इंडेंट के साथ प्रदर्शित होंगे।
डिफ़ॉल्ट रूप से यह false (अक्षम) — लीफ़ टेक्स्ट नोड्स को उनके पैरेंट के समान पंक्ति में रखा जाता है, बिना नए इंडेंट के।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


प्रत्येक नई पंक्ति के बाएँ इंडेंट के लिए ऑफ़सेट निर्दिष्ट करने की अनुमति देता है। यह बिना इकाई के शून्य‑से‑भिन्न मान नहीं हो सकता। डिफ़ॉल्ट रूप से यह 10pt है।


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


प्रत्येक नई पंक्ति के बाएँ इंडेंट के लिए ऑफ़सेट निर्दिष्ट करने की अनुमति देता है। यह बिना इकाई के शून्य‑से‑भिन्न मान नहीं हो सकता। डिफ़ॉल्ट रूप से यह 10pt है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


यह दर्शाता है कि इस XML स्वरूपण विकल्प के इस उदाहरण में डिफ़ॉल्ट मान है या नहीं


**Returns:**
boolean
