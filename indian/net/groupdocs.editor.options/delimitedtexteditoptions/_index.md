---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सेपरेटर डिलिमिटर का उपयोग करने वाले टेक्स्ट-आधारित Spreadsheet दस्तावेज़ जैसे CSV, टैब-आधारित आदि को लोड करने के विकल्प।"
type: docs
weight: 810
url: /hi/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ (CSV, टैब-आधारित आदि) को लोड करने के विकल्प, जो एक विभाजक (डिलिमिटर) का उपयोग करते हैं

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | डिलिमिटेड टेक्स्ट के लिए अनिवार्य सेपरेटर (डिलिमिटर) के साथ विकल्प क्लास का इंस्टेंस बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | टेक्स्ट-आधारित दस्तावेज़ में स्ट्रिंग को डेट डेटा में परिवर्तित किया जाए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। डिफ़ॉल्ट `false` है। |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | टेक्स्ट-आधारित दस्तावेज़ में स्ट्रिंग को संख्यात्मक डेटा में परिवर्तित किया जाए या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। डिफ़ॉल्ट `false` है। |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | इनपुट दस्तावेज़ प्रोसेसिंग के दौरान मेमोरी ऑप्टिमाइज़ेशन मैकेनिज़्म को सक्षम करता है, जो कुछ विशेष मामलों में प्रदर्शन को घटा सकता है, लेकिन दूसरी ओर मेमोरी उपयोग को कम करता है। बड़े दस्तावेज़ों को प्रोसेस करने और OutOfMemoryException का सामना करने पर उपयोगी है। डिफ़ॉल्ट `false` है (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है)। |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | टेक्स्ट‑आधारित स्प्रेडशीट दस्तावेज़ों के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | परिभाषित करता है कि क्रमिक डिलिमिटर को एक के रूप में माना जाए या नहीं। डिफ़ॉल्ट `false` है। |

### टिप्पणियाँ

https://en.wikipedia.org/wiki/Delimiter-separated_values

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
