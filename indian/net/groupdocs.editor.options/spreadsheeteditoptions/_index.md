---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी समर्थित स्प्रेडशीट Excel‑संगत फ़ॉर्मेट्स के दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 1110
url: /hi/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

सभी समर्थित स्प्रेडशीट (Excel-समर्थित) फॉर्मेट्स के दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | इनपुट स्प्रेडशीट दस्तावेज़ में छिपी वर्कशीट्स को बाहर रखने की अनुमति देता है, ताकि उन्हें पूरी तरह अनदेखा किया जा सके। डिफ़ॉल्ट रूप से फ़ॉल्स है — छिपी वर्कशीट्स उपलब्ध रहती हैं और सामान्य रूप से प्रोसेस की जाती हैं। |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | सक्षम होने पर, उत्पन्न HTML दस्तावेज़ में HTML टेबल में नीचे की ओर एक खाली छिपी पंक्ति शून्य ऊँचाई और खाली सेल्स के साथ होती है, जहाँ केवल चौड़ाई निर्दिष्ट की गई है। यह खाली सेल्स वाली पंक्ति प्रत्येक कॉलम के लिए सटीक चौड़ाई मान रखती है और HTML से स्प्रेडशीट में बैकवर्ड रूपांतरण को सुधारती है। डिफ़ॉल्ट रूप से यह सक्षम (`true`) है। |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | सक्षम होने पर, इनपुट स्प्रेडशीट दस्तावेज़ की खाली क्रमागत क्षैतिज सेल्स को संपादन योग्य HTML दस्तावेज़ में संबंधित `colspan` एट्रिब्यूट के साथ एकल सेल में मर्ज किया जाएगा। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है। |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | इनपुट स्प्रेडशीट दस्तावेज़ के कार्यपत्रक (टैब) का 0-आधारित सूचकांक निर्दिष्ट करने की अनुमति देता है, जिसे HTML में परिवर्तित किया जाना चाहिए (टिप्पणियों को देखें)। |

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
