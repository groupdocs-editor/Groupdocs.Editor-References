---
title: "FormatFamilies"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सिस्टम में उपलब्ध विभिन्न फ़ॉर्मेट परिवारों का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

सिस्टम में उपलब्ध विभिन्न फ़ॉर्मेट परिवारों का प्रतिनिधित्व करता है।

## Fields

| Field | विवरण |
| --- | --- |
|  | [EBook](#EBook) | eBook स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [Email](#Email) | Email स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [FixedLayout](#FixedLayout) | Fixed Layout स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [Presentation](#Presentation) | Presentation स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [Spreadsheet](#Spreadsheet) | Spreadsheet स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [Textual](#Textual) | Textual स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
|  | [WordProcessing](#WordProcessing) | Word Processing स्वरूप परिवार का प्रतिनिधित्व करता है। |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


eBook स्वरूप परिवार का प्रतिनिधित्व करता है।
Mobi स्वरूप के बारे में अधिक जानें
[here](../https://docs.fileformat.com/ebook/mobi/)
,
AZW3 फ़ॉर्मेट के बारे में
[here](../https://docs.fileformat.com/ebook/azw3/)
,
और ePub फ़ॉर्मेट के बारे में
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Email स्वरूप परिवार का प्रतिनिधित्व करता है।
ईमेल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Fixed Layout स्वरूप परिवार का प्रतिनिधित्व करता है।
विभिन्न दस्तावेज़ देखने या प्रकाशित करने वाले अनुप्रयोग उपयोगकर्ताओं को (Adobe Acrobat, XPS Viewer) खोलने और कभी‑कभी (Adobe InDesign) के साथ विशिष्ट फ़ॉर्मेट के दस्तावेज़ संपादित करने की अनुमति देते हैं।
इन अनुप्रयोगों द्वारा आमतौर पर तथाकथित “fixed-page” फ़ॉर्मेट के दस्तावेज़ उत्पन्न होते हैं।
ऐसा दस्तावेज़ फ़ॉर्मेट सटीक रूप से बताता है कि प्रत्येक पृष्ठ पर दस्तावेज़ की सामग्री कहाँ रखी गई है।
आंतरिक रूप से, PDF या XPS फ़ॉर्मेट में प्रत्येक पृष्ठ का विवरण तथा ड्रॉइंग निर्देश होते हैं, जो पृष्ठ पर सामग्री की व्यवस्था को निर्दिष्ट करते हैं।
यह इमेज फ़ॉर्मेट्स के समान है, जो बताता है कि सामग्री रास्टर या वेक्टर रूप में कहाँ प्रदर्शित होती है।


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Presentation स्वरूप परिवार का प्रतिनिधित्व करता है।
प्रेजेंटेशन फ़ॉर्मेट्स के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Spreadsheet स्वरूप परिवार का प्रतिनिधित्व करता है।
सभी बाइनरी, XML और टेक्स्टुअल स्प्रेडशीट फ़ॉर्मेट्स (जैसे CSV, TSV, सेमीकोलन‑डिलिमिटेड आदि जैसे विभाजक‑आधारित टेक्स्टुअल फ़ॉर्मेट्स को छोड़कर), जिनमें वर्कबुक को सहेजा जा सकता है।


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Textual स्वरूप परिवार का प्रतिनिधित्व करता है।
सभी पाठ्य (टेक्स्ट-आधारित) फ़ॉर्मेट को संलग्न करता है, जिसमें मार्कअप (XML, HTML) और अन्य शामिल हैं।


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Word Processing स्वरूप परिवार का प्रतिनिधित्व करता है।
वर्ड प्रोसेसिंग फ़ॉर्मेट्स के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME कोड दिए गए संसाधनों से प्राप्त किए गए हैं: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



