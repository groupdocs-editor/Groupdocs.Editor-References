---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी वर्डप्रोसेसिंग फ़ॉर्मेट को संलग्न करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

सभी WordProcessing फ़ॉर्मेट्स को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Word Processing फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing).

MIME कोड दिए गए संसाधनों से प्राप्त किए गए हैं:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Fields

| Field | विवरण |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 बाइनरी फ़ाइल फ़ॉर्मेट (DOC) उन दस्तावेज़ों को दर्शाता है जो Microsoft Word या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न किए जाते हैं। |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML मैक्रो-फ़्री दस्तावेज़ (DOCX) Microsoft Word दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। |
|
|  | [Dot](#Dot) | MS Word 97-2007 टेम्प्लेट (DOT) Microsoft Word द्वारा बनाए गए टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML मैक्रो-एनेबल्ड दस्तावेज़ (DOCM) फ़ाइलें Microsoft Word 2007 या उसके बाद के संस्करणों द्वारा उत्पन्न दस्तावेज़ हैं, जिनमें मैक्रो चलाने की क्षमता होती है। |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML मैक्रो-फ़्री टेम्प्लेट (DOTX) Microsoft Word द्वारा बनाए गए टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML मैक्रो-एनेबल्ड टेम्प्लेट (DOTM) Microsoft Word 2007 या उसके बाद के संस्करणों द्वारा बनाए गए टेम्प्लेट फ़ाइलों को दर्शाता है। |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत किया जाता है। |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि को दर्शाता है, जिसका उपयोग अनुप्रयोगों में किया जाता है। |
|
|  | [Odt](#Odt) | Open Document Format टेक्स्ट दस्तावेज़ (ODT) फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो वर्ड प्रोसेसिंग अनुप्रयोगों द्वारा बनाए जाते हैं और OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित होते हैं। |
|
|  | [Ott](#Ott) | Open Document Format टेक्स्ट दस्तावेज़ टेम्प्लेट (OTT) उन टेम्प्लेट दस्तावेज़ों को दर्शाते हैं जो OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप अनुप्रयोगों द्वारा उत्पन्न किए जाते हैं। |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML फ़ॉर्मेट \u2014 WordProcessingML या WordML (.XML). |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) की एक एनेमरेबल कलेक्शन प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) का एक इंस्टेंस पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 बाइनरी फ़ाइल फ़ॉर्मेट (DOC) उन दस्तावेज़ों को दर्शाता है जो Microsoft Word या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न किए जाते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML मैक्रो-फ़्री दस्तावेज़ (DOCX) Microsoft Word दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 टेम्प्लेट (DOT) Microsoft Word द्वारा बनाए गए टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML मैक्रो-एनेबल्ड दस्तावेज़ (DOCM) फ़ाइलें Microsoft Word 2007 या उसके बाद के संस्करणों द्वारा उत्पन्न दस्तावेज़ हैं, जिनमें मैक्रो चलाने की क्षमता होती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML मैक्रो-फ़्री टेम्प्लेट (DOTX) Microsoft Word द्वारा बनाए गए टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML मैक्रो-एनेबल्ड टेम्प्लेट (DOTM) Microsoft Word 2007 या उसके बाद के संस्करणों द्वारा बनाए गए टेम्प्लेट फ़ाइलों को दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत किया जाता है।


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि को दर्शाता है, जिसका उपयोग अनुप्रयोगों में किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format टेक्स्ट दस्तावेज़ (ODT) फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो वर्ड प्रोसेसिंग अनुप्रयोगों द्वारा बनाए जाते हैं और OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित होते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format टेक्स्ट दस्तावेज़ टेम्प्लेट (OTT) उन टेम्प्लेट दस्तावेज़ों को दर्शाते हैं जो OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप अनुप्रयोगों द्वारा उत्पन्न किए जाते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML फ़ॉर्मेट \u2014 WordProcessingML या WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


सभी [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) की एक एनेमरेबल कलेक्शन प्राप्त करता है।
मान: एक  IEnumerable{WordProcessingFormats}  जिसमें सभी [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) के इंस्टेंस शामिल हैं।


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) का एक इंस्टेंस पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

