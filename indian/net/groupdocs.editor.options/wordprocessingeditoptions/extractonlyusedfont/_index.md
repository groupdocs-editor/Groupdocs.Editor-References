---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या केवल दस्तावेज़ की पाठ्य सामग्री में उपयोग किए गए फ़ॉन्ट संसाधनों को निकाला जाए।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या केवल दस्तावेज़ की पाठ्य सामग्री में उपयोग किए गए फ़ॉन्ट संसाधनों को निकाला जाए।

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` यदि केवल उन फ़ॉन्ट संसाधनों को निकालना आवश्यक है, जो दस्तावेज़ की पाठ सामग्री में उपयोग होते हैं; अन्यथा, `false`। डिफ़ॉल्ट मान `false` है।

### टिप्पणियाँ

WordProcessing दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट 100% सीधे (किसी पाठ पर लागू) नहीं होते। ऐसी स्थिति हो सकती है जहाँ फ़ॉन्ट दस्तावेज़ में संदर्भित हो और एम्बेड भी किया गया हो, लेकिन किसी भी पाठ भाग पर लागू न हो। उदाहरण के लिए, कुछ फ़ॉन्ट किसी शैली से जुड़ा हो सकता है, लेकिन वह शैली पाठ के किसी भाग पर लागू नहीं होती। यह विकल्प इन मामलों को कैसे प्रोसेस किया जाए, इसे नियंत्रित करता है।

### संबंधित देखें

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
