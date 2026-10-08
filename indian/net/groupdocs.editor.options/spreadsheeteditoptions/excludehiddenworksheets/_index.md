---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इनपुट Spreadsheet दस्तावेज़ में छिपी वर्कशीट्स को बाहर रखने की अनुमति देता है ताकि उन्हें पूरी तरह अनदेखा किया जा सके। डिफ़ॉल्ट रूप में यह false है; छिपी वर्कशीट्स उपलब्ध रहती हैं और सामान्य रूप से प्रोसेस की जाती हैं।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

इनपुट स्प्रेडशीट दस्तावेज़ में छिपी वर्कशीट्स को बाहर रखने की अनुमति देता है, ताकि उन्हें पूरी तरह अनदेखा किया जा सके। डिफ़ॉल्ट रूप से फ़ॉल्स है — छिपी वर्कशीट्स उपलब्ध रहती हैं और सामान्य रूप से प्रोसेस की जाती हैं।

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### टिप्पणियाँ

कई बाइनरी Spreadsheet फ़ॉर्मेट (जैसे XLSX) छिपी वर्कशीट्स (टैब) की अवधारणा का समर्थन करते हैं। ऐसे फ़ॉर्मेट के दस्तावेज़ में, यदि एक से अधिक वर्कशीट हैं, तो अतिरिक्त छिपी वर्कशीट्स हो सकती हैं। डिफ़ॉल्ट रूप में ये छिपी वर्कशीट्स प्रोसेसिंग के लिए उपलब्ध रहती हैं, लेकिन इस विकल्प के साथ उन्हें अनदेखा किया जा सकता है, जैसे कि ये छिपी वर्कशीट्स मौजूद नहीं हैं। जब यह विकल्प सक्षम होता है, तो आप '[`WorksheetIndex`](../worksheetindex)' प्रॉपर्टी के साथ छिपी वर्कशीट का चयन नहीं कर सकते।

### संबंधित देखें

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
