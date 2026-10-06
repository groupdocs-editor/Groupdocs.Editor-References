---
title: "TextualFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मार्कअप XML, HTML और अन्य सहित सभी पाठ-आधारित स्वरूपों को समाहित करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

सभी पाठ्य (टेक्स्ट-आधारित) फ़ॉर्मेट को संलग्न करता है, जिसमें मार्कअप (XML, HTML) और अन्य शामिल हैं।
निम्नलिखित स्वरूप शामिल हैं:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Fields

| Field | विवरण |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language दस्तावेज़ (HTML) ब्राउज़र में प्रदर्शित करने के लिए बनाई गई वेब पेजों के एक्सटेंशन है। |
|
|  | [Xml](#Xml) | eXtensible Markup Language दस्तावेज़ (XML) HTML के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग उपयोग करने में अलग है। |
|
|  | [Txt](#Txt) | Plain Text Document (TXT) एक ऐसा पाठ दस्तावेज़ दर्शाता है जिसमें पंक्तियों के रूप में साधारण पाठ होता है। |
|
|  | [Md](#Md) | Markdown एक हल्की मार्कअप भाषा है जो साधारण‑पाठ संपादक का उपयोग करके स्वरूपित पाठ बनाने के लिए उपयोग की जाती है। |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) एक खुला मानक फ़ाइल स्वरूप है जो डेटा साझा करने के लिए मानव‑पठनीय पाठ का उपयोग करके डेटा को संग्रहीत और प्रसारित करता है। |
|
|  | [Mhtml](#Mhtml) | MIME एन्कैप्सुलेशन ऑफ एग्रीगेट HTML डॉक्यूमेंट्स एक वेब पेज आर्काइव स्वरूप है जो एकल कंप्यूटर फ़ाइल में HTML कोड और उसके संबंधित संसाधनों को संयोजित करने के लिए उपयोग किया जाता है। |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help माइक्रोसॉफ्ट का स्वामित्व वाला ऑनलाइन सहायता बाइनरी स्वरूप है, जिसमें HTML पृष्ठों का संग्रह, एक अनुक्रमणिका और अन्य नेविगेशन टूल शामिल हैं। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [TextualFormats](../../com.groupdocs.editor.formats/textualformats) की एक गणनीय संग्रह प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [TextualFormats](../../com.groupdocs.editor.formats/textualformats) का एक उदाहरण पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [TextualFormats](../../com.groupdocs.editor.formats/textualformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language दस्तावेज़ (HTML) ब्राउज़र में प्रदर्शित करने के लिए बनाई गई वेब पेजों के एक्सटेंशन है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language दस्तावेज़ (XML) HTML के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग उपयोग करने में अलग है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) एक ऐसा पाठ दस्तावेज़ दर्शाता है जिसमें पंक्तियों के रूप में साधारण पाठ होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown एक हल्की मार्कअप भाषा है जो साधारण‑पाठ संपादक का उपयोग करके स्वरूपित पाठ बनाने के लिए उपयोग की जाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) एक खुला मानक फ़ाइल स्वरूप है जो डेटा साझा करने के लिए मानव‑पठनीय पाठ का उपयोग करके डेटा को संग्रहीत और प्रसारित करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME एन्कैप्सुलेशन ऑफ एग्रीगेट HTML डॉक्यूमेंट्स एक वेब पेज आर्काइव स्वरूप है जो एकल कंप्यूटर फ़ाइल में HTML कोड और उसके संबंधित संसाधनों को संयोजित करने के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help माइक्रोसॉफ्ट का स्वामित्व वाला ऑनलाइन सहायता बाइनरी स्वरूप है, जिसमें HTML पृष्ठों का संग्रह, एक अनुक्रमणिका और अन्य नेविगेशन टूल शामिल हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


सभी [TextualFormats](../../com.groupdocs.editor.formats/textualformats) की एक गणनीय संग्रह प्राप्त करता है।
मान: एक IEnumerable{TextualFormats} जिसमें सभी [TextualFormats](../../com.groupdocs.editor.formats/textualformats) के उदाहरण शामिल हैं।


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [TextualFormats](../../com.groupdocs.editor.formats/textualformats) का एक उदाहरण पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [TextualFormats](../../com.groupdocs.editor.formats/textualformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

