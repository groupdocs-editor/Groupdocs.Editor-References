---
title: SpreadsheetFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: सभ बइनर एक्सएमएल और टेक्स्टुअल स्प्रैडशट स्वरूपं क समहत करत है सएसव टएसव अर्धवरमसमंकत आद जैसे वभजक वले सभ टेक्स्ट डलमटरआधरत स्वरूपं क छड़कर जसमें कर्यपुस्तक क सहेज ज सकत है में नम्नलखत प्ररूप शमल हैं Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . स्प्रेडशट प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /hi/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

सभी बाइनरी, एक्सएमएल और टेक्स्टुअल स्प्रैडशीट स्वरूपों को समाहित करता है (सीएसवी, टीएसवी, अर्धविराम-सीमांकित आदि जैसे विभाजक वाले सभी टेक्स्ट डिलिमिटर-आधारित स्वरूपों को छोड़कर), जिसमें कार्यपुस्तिका को सहेजा जा सकता है। में निम्नलिखित प्रारूप शामिल हैं: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . स्प्रेडशीट प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | लोअर केस में इस स्प्रेडशीट प्रारूप का एक एक्सटेंशन (अग्रणी डॉट वर्ण के बिना) लौटाता है |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | इस प्रारूप के लिए एक MIME कोड लौटाता है |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | इस स्प्रैडशीट प्रारूप का औपचारिक पूरा नाम लौटाता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | का उदाहरण देता है[`SpreadsheetFormats`](../spreadsheetformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट वस्तु के बराबर है, जो संभवतः बॉक्सिंग स्प्रेडशीटफॉर्मैट्स के बराबर है |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट स्प्रेडशीटफॉर्मैट्स उदाहरण के बराबर है |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | समानता पर दिए गए दो स्प्रेडशीटफॉर्मेट्स उदाहरणों की जांच करता है |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | असमानता पर दिए गए दो स्प्रेडशीटफॉर्मेट्स उदाहरणों की जांच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | अल्पविराम से अलग किए गए मान (CSV) दस्तावेज़ सादे पाठ का प्रतिनिधित्व करते हैं जिनमें अल्पविराम से अलग किए गए मान वाले डेटा के रिकॉर्ड होते हैं। CSV फ़ाइल में प्रत्येक पंक्ति फ़ाइल में निहित रिकॉर्ड के सेट से एक नया रिकॉर्ड है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | डेटा इंटरचेंज फ़ॉर्मेट (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | फ्लैट ओपन डॉक्यूमेंट स्प्रेडशीट (FODS) — एक असम्पीडित XML दस्तावेज़ के रूप में संग्रहीत |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument स्प्रेडशीट (ODS) OpenDocument स्प्रेडशीट दस्तावेज़ प्रारूप के लिए है जो उपयोगकर्ता द्वारा संपादन योग्य हैं। डेटा को ODF फ़ाइल में पंक्तियों और स्तंभों में संग्रहीत किया जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | स्प्रेडशीटएमएल - माइक्रोसॉफ्ट ऑफिस एक्सेल 2002 और एक्सेल 2003 एक्सएमएल फॉर्मेट |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice या OpenOffice.org Calc XML स्प्रेडशीट (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | टैब-पृथक मान (TSV) फ़ाइल स्वरूप सादे पाठ प्रारूप में टैब के साथ अलग किए गए डेटा का प्रतिनिधित्व करता है। विभिन्न अनुप्रयोगों के बीच आयात और निर्यात करने के लिए CSV के समान फ़ाइल प्रारूप का उपयोग संरचित तरीके से डेटा के संगठन के लिए किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | एक्सेल ऐड-इन (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | एक्सेल 97-2003 बाइनरी फ़ाइल फ़ॉर्मेट (XLS) उन फ़ाइलों का प्रतिनिधित्व करता है जिन्हें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा बनाया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | एक्सेल बाइनरी वर्कबुक (XLSB) एक्सेल बाइनरी फाइल फॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो एक्सेल वर्कबुक सामग्री को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | ऑफिस ओपन एक्सएमएल वर्कबुक मैक्रो-इनेबल्ड (XLSM) एक प्रकार की स्प्रेशीट फाइल है जो मैक्रो का समर्थन करती है। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | ऑफिस ओपन एक्सएमएल वर्कबुक मैक्रो-फ्री (एक्सएलएसएक्स) उन दस्तावेजों का प्रतिनिधित्व करता है जो माइक्रोसॉफ्ट द्वारा माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज के साथ पेश किए गए थे। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | एक्सेल 97-2003 टेम्प्लेट (XLT) माइक्रोसॉफ्ट एक्सेल के साथ बनाई गई टेम्प्लेट फाइलों का प्रतिनिधित्व करता है जो एक स्प्रेडशीट एप्लिकेशन है जो माइक्रोसॉफ्ट ऑफिस सूट के हिस्से के रूप में आता है। Microsoft Office 97-2003 ने नई XLT फ़ाइलों को बनाने के साथ-साथ इन्हें खोलने का भी समर्थन किया। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | ऑफिस ओपन एक्सएमएल टेम्पलेट मैक्रो-सक्षम (एक्सएलटीएम) उन फाइलों का प्रतिनिधित्व करता है जो माइक्रोसॉफ्ट एक्सेल द्वारा मैक्रो-सक्षम टेम्पलेट फाइलों के रूप में उत्पन्न होती हैं। XLTM फाइलें संरचना में XLTX के समान हैं, इसके अलावा बाद में मैक्रोज़ के साथ टेम्पलेट फ़ाइलों को बनाने का समर्थन नहीं करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | ऑफिस ओपन एक्सएमएल टेम्पलेट मैक्रो-फ्री (एक्सएलटीएक्स) फ़ाइल माइक्रोसॉफ्ट एक्सेल टेम्पलेट का प्रतिनिधित्व करती है जो ऑफिस ओपनएक्सएमएल फ़ाइल प्रारूप विनिर्देशों पर आधारित हैं। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसका उपयोग XLTX फ़ाइल बनाने के लिए किया जा सकता है जो XLTX फ़ाइल में निर्दिष्ट सेटिंग्स को प्रदर्शित करती है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा स्प्रेडशीट प्रारूपों पर असंख्य संभावनाएं प्रदान करता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | IEnumerable जेनेरिक इंटरफ़ेस लागू करता है, जो स्प्रेडशीटफ़ॉर्मैट्स टाइप के लिए 'foreach' संभावना को सक्षम करता है |

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
