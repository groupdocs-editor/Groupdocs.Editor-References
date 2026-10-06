---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सादा टेक्स्ट TXT दस्तावेज़ उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 41
url: /hi/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

सादा टेक्स्ट (TXT) उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
दस्तावेज़

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
सहेजना
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी |
सहेजना
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | निर्दिष्ट करता है कि प्रत्येक BiDi रन से पहले द्विदिश चिह्न जोड़ना है या नहीं जब |
सादा टेक्स्ट फ़ॉर्मेट में निर्यात किया जा रहा हो।
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | निर्दिष्ट करता है कि प्रत्येक BiDi रन से पहले द्विदिश चिह्न जोड़ना है या नहीं जब |
सादा टेक्स्ट फ़ॉर्मेट में निर्यात करना
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | निर्दिष्ट करता है कि प्रोग्राम को तालिकाओं की लेआउट को संरक्षित करने का प्रयास करना चाहिए या नहीं |
जब सादा टेक्स्ट फ़ॉर्मेट में सहेजा जा रहा हो।
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | निर्दिष्ट करता है कि प्रोग्राम को तालिकाओं की लेआउट को संरक्षित करने का प्रयास करना चाहिए या नहीं |
जब सादा टेक्स्ट फ़ॉर्मेट में सहेजा जा रहा हो।
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
सहेजना


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


पाठ दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो इसके लिए लागू की जाएगी
सहेजना


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


निर्दिष्ट करता है कि प्रत्येक BiDi रन से पहले द्विदिश चिह्न जोड़ना है या नहीं जब
सादा टेक्स्ट फ़ॉर्मेट में निर्यात करना। डिफ़ॉल्ट 'false' है \\u2014 BiDi चिह्न न जोड़ें।


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


निर्दिष्ट करता है कि प्रत्येक BiDi रन से पहले द्विदिश चिह्न जोड़ना है या नहीं जब
सादा टेक्स्ट फ़ॉर्मेट में निर्यात करना


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


निर्दिष्ट करता है कि प्रोग्राम को तालिकाओं की लेआउट को संरक्षित करने का प्रयास करना चाहिए या नहीं
जब सादा टेक्स्ट फ़ॉर्मेट में सहेजा जा रहा हो। डिफ़ॉल्ट मान false है।


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


निर्दिष्ट करता है कि प्रोग्राम को तालिकाओं की लेआउट को संरक्षित करने का प्रयास करना चाहिए या नहीं
जब सादा टेक्स्ट फ़ॉर्मेट में सहेजा जा रहा हो। डिफ़ॉल्ट मान false है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

