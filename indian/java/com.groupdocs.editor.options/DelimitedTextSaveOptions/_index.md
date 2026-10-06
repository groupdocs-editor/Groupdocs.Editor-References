---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सेपरेटर डिलिमीटर का उपयोग करने वाले टेक्स्ट‑आधारित स्प्रेडशीट दस्तावेज़ (CSV, टैब‑आधारित आदि) को उत्पन्न करने और सहेजने के विकल्प शामिल करता है"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ उत्पन्न करने और सहेजने के विकल्प शामिल हैं
(CSV, टैब-आधारित आदि), जो एक विभाजक (डिलिमिटर) का उपयोग करते हैं


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | यह पैरामीटररहित कंस्ट्रक्टर DelimitedTextSaveOptions का एक नया इंस्टेंस बनाता है जिसमें डिफ़ॉल्ट विभाजक सेमीकोलन (;) है (इसे बाद में संशोधित किया जा सकता है |
विभाजक
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) प्रॉपर्टी)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | विलंबित टेक्स्ट के लिए आवश्यक विकल्प वर्ग का एक इंस्टेंस बनाता है |
सेपरेटर (डिलिमिटर)
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
स्प्रेडशीट दस्तावेज़
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
स्प्रेडशीट दस्तावेज़
|
|  | [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ के लिए एन्कोडिंग सेट करने की अनुमति देता है। |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ के लिए एन्कोडिंग सेट करने की अनुमति देता है। |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | यह संकेत देता है कि क्या अग्रणी खाली पंक्तियों और स्तंभों को इस प्रकार ट्रिम किया जाना चाहिए |
जैसा कि MS Excel करता है
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | यह संकेत देता है कि क्या अग्रणी खाली पंक्तियों और स्तंभों को इस प्रकार ट्रिम किया जाना चाहिए |
जैसा कि MS Excel करता है
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | यह दर्शाता है कि क्या खाली पंक्तियों के लिए विभाजक आउटपुट किए जाने चाहिए। |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | यह दर्शाता है कि क्या खाली पंक्तियों के लिए विभाजक आउटपुट किए जाने चाहिए। |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


यह पैरामीटररहित कंस्ट्रक्टर DelimitedTextSaveOptions का एक नया इंस्टेंस बनाता है जिसमें डिफ़ॉल्ट विभाजक सेमीकोलन (;) है (इसे बाद में संशोधित किया जा सकता है
विभाजक
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) प्रॉपर्टी)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


विलंबित टेक्स्ट के लिए आवश्यक विकल्प वर्ग का एक इंस्टेंस बनाता है
सेपरेटर (डिलिमिटर)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | सेपरेटर | java.lang.String | टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ों के लिए स्ट्रिंग विभाजक (डिलिमिटर) |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है
स्प्रेडशीट दस्तावेज़


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


टेक्स्ट-आधारित के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है
स्प्रेडशीट दस्तावेज़


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ के लिए एन्कोडिंग सेट करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट (और यदि निर्दिष्ट नहीं किया गया हो) UTF8 है।


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ के लिए एन्कोडिंग सेट करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट (और यदि निर्दिष्ट नहीं किया गया हो) UTF8 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


यह संकेत देता है कि क्या अग्रणी खाली पंक्तियों और स्तंभों को इस प्रकार ट्रिम किया जाना चाहिए
जैसा कि MS Excel करता है


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


यह संकेत देता है कि क्या अग्रणी खाली पंक्तियों और स्तंभों को इस प्रकार ट्रिम किया जाना चाहिए
जैसा कि MS Excel करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


यह दर्शाता है कि क्या खाली पंक्तियों के लिए विभाजक आउटपुट किए जाने चाहिए। डिफ़ॉल्ट
मान false है, जिसका अर्थ है कि खाली पंक्ति की सामग्री खाली होगी।


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


यह दर्शाता है कि क्या खाली पंक्तियों के लिए विभाजक आउटपुट किए जाने चाहिए। डिफ़ॉल्ट
मान false है, जिसका अर्थ है कि खाली पंक्ति की सामग्री खाली होगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

