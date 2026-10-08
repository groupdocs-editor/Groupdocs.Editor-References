---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इनपुट Spreadsheet दस्तावेज़ की वर्कशीट टैब का 0‑आधारित इंडेक्स निर्दिष्ट करने की अनुमति देता है जिसे HTML में परिवर्तित किया जाना चाहिए; विवरण देखें।"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

इनपुट स्प्रेडशीट दस्तावेज़ के कार्यपत्रक (टैब) का 0-आधारित सूचकांक निर्दिष्ट करने की अनुमति देता है, जिसे HTML में परिवर्तित किया जाना चाहिए (टिप्पणियों को देखें)।

```csharp
public int WorksheetIndex { get; set; }
```

### टिप्पणियाँ

अधिकांश Spreadsheet दस्तावेज़ टैब की अवधारणा का समर्थन करते हैं, अर्थात वे मल्टी‑टैब हो सकते हैं। दूसरी ओर, HTML फ़ॉर्मेट ऐसी संरचना का समर्थन नहीं करता। इसलिए GroupDocs.Editor इनपुट दस्तावेज़ के केवल एक विशिष्ट टैब को HTML में परिवर्तित कर सकता है, और यह विकल्प उसे निर्दिष्ट करने की अनुमति देता है। टैब इंडेक्स 0‑आधारित है, नकारात्मक मान प्रतिबंधित हैं। यदि निर्दिष्ट इंडेक्स सभी टैबों की संख्या से अधिक है, तो अपवाद उत्पन्न होगा। यदि इनपुट Spreadsheet दस्तावेज़ में केवल एक टैब है, तो यह विकल्प अनदेखा किया जाएगा। डिफ़ॉल्ट मान 0 (पहला टैब) है।

### संबंधित देखें

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
