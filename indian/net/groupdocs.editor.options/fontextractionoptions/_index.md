---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ॉन्ट एक्सट्रैक्शन विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट निकालने हैं और कहाँ से"
type: docs
weight: 890
url: /hi/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

फ़ॉन्ट एक्सट्रैक्शन विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट निकालने हैं और कहाँ से

```csharp
public enum FontExtractionOptions
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| NotExtract | `0` | दस्तावेज़ या सिस्टम से कोई भी फ़ॉन्ट संसाधन नहीं निकालता है। डिफ़ॉल्ट मान। |
| ExtractAllEmbedded | `1` | इनपुट Word दस्तावेज़ में एम्बेड किए गए सभी फ़ॉन्ट संसाधनों को निकालता है, चाहे वे कस्टम हों या सिस्टम। |
| ExtractEmbeddedWithoutSystem | `2` | केवल उन एम्बेड किए गए फ़ॉन्ट संसाधनों को निकालता है, जो कस्टम हैं (सिस्टम नहीं)। |
| ExtractAll | `3` | इनपुट WordProcessing दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट्स को निकालने का प्रयास करता है, जिसमें सिस्टम फ़ॉन्ट्स भी शामिल हैं। |

### संबंधित देखें

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
