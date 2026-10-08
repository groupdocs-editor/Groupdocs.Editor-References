---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "बाइनरी Spreadsheet Cells Excelcompatible दस्तावेज़ जैसे XLSX, ODS आदि को Editor क्लास में लोड करने के विकल्प शामिल करता है।"
type: docs
weight: 1120
url: /hi/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

XLS(X), ODS आदि जैसे बाइनरी स्प्रेडशीट (Cells, Excel-समर्थित) दस्तावेज़ों को Editor क्लास में लोड करने के विकल्प शामिल करता है

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | डिफ़ॉल्ट पैरामीटरलेस कंस्ट्रक्टर - सभी पैरामीटरों के डिफ़ॉल्ट मान होते हैं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मैकेनिज़्म को सक्षम करता है, जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर मेमोरी उपयोग को कम करता है। बड़े दस्तावेज़ों को प्रोसेस करने और OutOfMemoryException का सामना करने पर उपयोगी है। डिफ़ॉल्ट `false` है (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है)। |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | यदि एन्कोडेड हो तो Spreadsheet दस्तावेज़ खोलने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित और प्राप्त करने की अनुमति देता है। पासवर्ड न उपयोग करने के लिए NULL या खाली स्ट्रिंग सेट करें (डिफ़ॉल्ट मान)। |

### संबंधित देखें

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
