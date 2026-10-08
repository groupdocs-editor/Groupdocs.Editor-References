---
title: "स्प्रेडशीट फ़ॉर्मेट्स"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "वर्कबुक को सहेजे जा सकने वाले सभी बाइनरी XML और टेक्स्टुअल स्प्रेडशीट फ़ॉर्मेट को एन्कैप्सुलेट करता है, जिसमें CSV, TSV, सेमीकोलन‑डिलिमिटेड आदि जैसे विभाजक‑आधारित टेक्स्टुअल फ़ॉर्मेट शामिल नहीं हैं। निम्नलिखित फ़ॉर्मेट शामिल हैं Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv। स्प्रेडशीट फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ https//wiki.fileformat.com/spreadsheet देखें।"
type: docs
weight: 130
url: /hi/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

वर्कबुक को सहेजे जा सकने वाले सभी बाइनरी, XML और टेक्स्टुअल स्प्रेडशीट फ़ॉर्मेट को एन्कैप्सुलेट करता है (जिसमें CSV, TSV, सेमीकोलन‑डिलिमिटेड आदि जैसे विभाजक‑आधारित टेक्स्टुअल फ़ॉर्मेट शामिल नहीं हैं), जिसमें वर्कबुक को सहेजा जा सकता है। निम्नलिखित फ़ॉर्मेट शामिल हैं: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). स्प्रेडशीट फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet) देखें।

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | सभी [`SpreadsheetFormats`](../spreadsheetformats) की एक enumerable collection प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार [`SpreadsheetFormats`](../spreadsheetformats) का एक instance प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`SpreadsheetFormats`](../spreadsheetformats) ऑब्जेक्ट में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | कॉमा सेपरेटेड वैल्यूज़ (CSV)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/csv/) देखें। |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | डेटा इंटरचेंज फ़ॉर्मेट (DIF)। |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | फ़्लैट OpenDocument स्प्रेडशीट (FODS)। |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument स्प्रेडशीट (ODS)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/ods) देखें। |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — माइक्रोसॉफ्ट ऑफिस एक्सेल 2002 और एक्सेल 2003 XML फ़ॉर्मेट। |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice या OpenOffice.org Calc XML स्प्रेडशीट (SXC)। |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | टैब-सेपरेटेड वैल्यूज़ (TSV)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/tsv/) देखें। |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | एक्सेल ऐड-इन (XLAM)। |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | एक्सेल 97-2003 बाइनरी फ़ाइल फ़ॉर्मेट (XLS)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xls) देखें। |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | एक्सेल बाइनरी वर्कबुक (XLSB)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb) देखें। |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | ऑफ़िस ओपन XML वर्कबुक मैक्रो-एनेबल्ड (XLSM)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm) देखें। |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | ऑफ़िस ओपन XML वर्कबुक मैक्रो-फ्री (XLSX)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx) देखें। |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | एक्सेल 97-2003 टेम्प्लेट (XLT)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xlt) देखें। |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | ऑफ़िस ओपन XML टेम्प्लेट मैक्रो-एनेबल्ड (XLTM)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xltm) देखें। |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | ऑफ़िस ओपन XML टेम्प्लेट मैक्रो-फ्री (XLTX)। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/xltx) देखें। |

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
