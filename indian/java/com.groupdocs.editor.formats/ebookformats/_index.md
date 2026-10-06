---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी ईबुक फ़ॉर्मेट को संलग्न करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

सभी eBook फ़ॉर्मेट को समाहित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Mobi फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/ebook/mobi/), और ePub फ़ॉर्मेट के बारे में [यहाँ](../https://docs.fileformat.com/ebook/epub/)।

## Fields

| Field | विवरण |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI वह नाम है जो MobiPocket रीडर के लिए विकसित फ़ॉर्मेट को दिया गया है। |
|
|  | [Epub](#Epub) | इलेक्ट्रॉनिक पब्लिकेशन (IDPF ePub) फ़ॉर्मेट एक e-book फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। |
|
|  | [Azw3](#Azw3) | AZW3, जिसे Kindle Format 8 (KF8) भी कहा जाता है, Amazon Kindle डिवाइसों के लिए विकसित AZW e‑book डिजिटल फ़ाइल फ़ॉर्मेट का संशोधित संस्करण है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) की एक enumerable संग्रह प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) का एक इंस्टेंस पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI वह नाम है जो MobiPocket रीडर के लिए विकसित फ़ॉर्मेट को दिया गया है। इसे PRC, AZW भी कहा जाता है।
वर्तमान में इसे Amazon द्वारा थोड़ा अलग DRM योजना के साथ उपयोग किया जाता है और इसे AZW कहा जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


इलेक्ट्रॉनिक पब्लिकेशन (IDPF ePub) फ़ॉर्मेट एक e-book फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, जिसे Kindle Format 8 (KF8) भी कहा जाता है, Amazon Kindle डिवाइसों के लिए विकसित AZW e‑book डिजिटल फ़ाइल फ़ॉर्मेट का संशोधित संस्करण है।
यह फ़ॉर्मेट पुराने AZW फ़ाइलों में सुधार है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


सभी [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) की एक enumerable संग्रह प्राप्त करता है।
मान: एक  IEnumerable{EBookFormats}  जिसमें सभी [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) के इंस्टेंस शामिल हैं।


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) का एक इंस्टेंस पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

