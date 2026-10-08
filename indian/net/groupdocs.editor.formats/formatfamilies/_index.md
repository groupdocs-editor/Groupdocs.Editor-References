---
title: "फ़ॉर्मेट परिवार"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सिस्टम में उपलब्ध विभिन्न फ़ॉर्मेट परिवारों का प्रतिनिधित्व करता है।"
type: docs
weight: 110
url: /hi/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

सिस्टम में उपलब्ध विभिन्न फ़ॉर्मेट परिवारों का प्रतिनिधित्व करता है।

```csharp
public class FormatFamilies : FormatFamilyBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | eBook फ़ॉर्मेट परिवार को दर्शाता है। Mobi फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/ebook/mobi/), AZW3 फ़ॉर्मेट के बारे में [यहाँ](https://docs.fileformat.com/ebook/azw3/), और ePub फ़ॉर्मेट के बारे में [यहाँ](https://docs.fileformat.com/ebook/epub/) देखें। |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | ईमेल फ़ॉर्मेट परिवार को दर्शाता है। ईमेल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/) देखें। |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | फ़िक्स्ड लेआउट फ़ॉर्मेट परिवार को दर्शाता है। विभिन्न दस्तावेज़ देखने या प्रकाशन अनुप्रयोग उपयोगकर्ताओं को विशिष्ट फ़ॉर्मेट के दस्तावेज़ खोलने (Adobe Acrobat, XPS Viewer) और कभी‑कभी संपादित करने (Adobe InDesign) की अनुमति देते हैं। ये अनुप्रयोग आमतौर पर तथाकथित “fixed-page” फ़ॉर्मेट दस्तावेज़ बनाते हैं। ऐसा दस्तावेज़ फ़ॉर्मेट सटीक रूप से बताता है कि प्रत्येक पृष्ठ पर दस्तावेज़ की सामग्री कहाँ रखी गई है। आंतरिक रूप से, PDF या XPS फ़ॉर्मेट प्रत्येक पृष्ठ का विवरण, साथ ही ड्राइंग निर्देश शामिल करता है, जो पृष्ठ पर सामग्री के लेआउट को निर्दिष्ट करता है। यह इमेज फ़ॉर्मेट्स के समान है, जो बताता है कि सामग्री रास्टर या वेक्टर रूप में कहाँ प्रदर्शित होती है। |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | प्रेज़ेंटेशन फ़ॉर्मेट परिवार को दर्शाता है। प्रेज़ेंटेशन फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation) देखें। |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | स्प्रेडशीट फ़ॉर्मेट परिवार को दर्शाता है। सभी बाइनरी, XML और टेक्स्टुअल स्प्रेडशीट फ़ॉर्मेट (जिनमें CSV, TSV, सेमीकोलन‑डिलिमिटेड आदि जैसे विभाजक‑आधारित टेक्स्टुअल फ़ॉर्मेट शामिल नहीं हैं), जिनमें वर्कबुक को सहेजा जा सकता है। |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | टेक्स्टुअल फ़ॉर्मेट परिवार को दर्शाता है। यह सभी टेक्स्टुअल (टेक्स्ट‑आधारित) फ़ॉर्मेट को एन्कैप्सुलेट करता है, जिसमें मार्कअप (XML, HTML) और अन्य शामिल हैं। |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | वर्ड प्रोसेसिंग फ़ॉर्मेट परिवार को दर्शाता है। वर्ड प्रोसेसिंग फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing) देखें। |

### संबंधित देखें

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
