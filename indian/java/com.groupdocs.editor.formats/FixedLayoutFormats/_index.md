---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी fixed-layout (जिसे fixed-page भी कहा जाता है) फ़ॉर्मेट्स को सम्मिलित करता है, जिसमें PDF और XPS शामिल हैं, लेकिन इसमें रास्टर इमेजेज़ नहीं हैं।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

सभी निश्चित-लेआउट (जिसे \"फिक्स्ड-पेज\" भी कहा जाता है) फ़ॉर्मेट को संलग्न करता है, जिसमें PDF और XPS शामिल हैं (यह रास्टर छवियों को शामिल नहीं करता)।

<br />

*** ** * ** ***

विभिन्न दस्तावेज़ देखने या प्रकाशित करने वाले अनुप्रयोग उपयोगकर्ताओं को (Adobe Acrobat, XPS Viewer) खोलने और कभी‑कभी (Adobe InDesign) के साथ विशिष्ट फ़ॉर्मेट के दस्तावेज़ संपादित करने की अनुमति देते हैं। इन अनुप्रयोगों द्वारा आमतौर पर तथाकथित “fixed-page” फ़ॉर्मेट के दस्तावेज़ उत्पन्न होते हैं। ऐसा दस्तावेज़ फ़ॉर्मेट सटीक रूप से बताता है कि प्रत्येक पृष्ठ पर दस्तावेज़ की सामग्री कहाँ रखी गई है। आंतरिक रूप से, PDF या XPS फ़ॉर्मेट में प्रत्येक पृष्ठ का विवरण तथा ड्रॉइंग निर्देश होते हैं, जो पृष्ठ पर सामग्री की व्यवस्था को निर्दिष्ट करते हैं। यह इमेज फ़ॉर्मेट्स के समान है, जो बताता है कि सामग्री रास्टर या वेक्टर रूप में कहाँ प्रदर्शित होती है।

<br />


## Fields

| Field | विवरण |
| --- | --- |
|  | [Pdf](#Pdf) | पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट (PDF) Adobe द्वारा 1990 के दशक में बनाया गया एक दस्तावेज़ प्रकार है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) की एक एनेरेबल कलेक्शन प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) का एक इंस्टेंस पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट (PDF) Adobe द्वारा 1990 के दशक में बनाया गया एक दस्तावेज़ प्रकार है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री को एक ऐसे मानक के रूप में प्रस्तुत करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


सभी [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) की एक एनेरेबल कलेक्शन प्राप्त करता है।
मान: एक IEnumerable{FixedLayoutFormats} जिसमें सभी [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) के इंस्टेंस शामिल हैं।


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) का एक इंस्टेंस पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

