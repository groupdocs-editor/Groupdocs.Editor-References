---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "XML (eXtensible Markup Language) दस्तावेज़ों को संपादित करने और उन्हें HTML में परिवर्तित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1270
url: /hi/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

XML (eXtensible Markup Language) दस्तावेज़ों को संपादित करने और उन्हें HTML में परिवर्तित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | एट्रिब्यूट मानों के लिए कोटेशन प्रकार (सिंगल या डबल कोट) निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट रूप से डबल कोट होते हैं। |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | टेक्स्ट दस्तावेज़ की कैरेक्टर एन्कोडिंग, जो उसके खोलने पर लागू होगी। डिफ़ॉल्ट रूप से null है — आंतरिक दस्तावेज़ एन्कोडिंग लागू होगी। |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | क्षतिग्रस्त XML संरचना को ठीक करने के तंत्र को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम है (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | XML फ़ॉर्मेटिंग को समायोजित करने की अनुमति देता है, जो XML संरचना पर लागू होगी, जब इसे HTML में प्रदर्शित किया जाता है। डिफ़ॉल्ट फ़ॉर्मेटिंग उपयोग की जाती है और समायोज्य है। null नहीं हो सकता। |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | XML हाइलाइटिंग को समायोजित करने की अनुमति देता है, जो XML संरचना पर लागू होगी, जब इसे HTML में प्रदर्शित किया जाता है। डिफ़ॉल्ट हाइलाइटिंग उपयोग की जाती है और समायोज्य है। null नहीं हो सकता। |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | एट्रिब्यूट मानों में ईमेल पते की पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | URI पहचान एल्गोरिदम को सक्षम करने की अनुमति देता है |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | इंटीर-टैग टेक्स्ट में अंत में आने वाले व्हाइटस्पेस को ट्रंकेट करने को सक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम (false) है — अंत में आने वाले व्हाइटस्पेस संरक्षित रहेंगे। |

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
