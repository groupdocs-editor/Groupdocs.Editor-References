---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ॉन्ट एम्बेडिंग विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट संसाधन आउटपुट वर्डप्रोसेसिंग या PDF दस्तावेज़ में एम्बेड किए जाने चाहिए"
type: docs
weight: 880
url: /hi/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

फ़ॉन्ट एम्बेडिंग विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट संसाधन आउटपुट वर्डप्रोसेसिंग या PDF दस्तावेज़ में एम्बेड किए जाने चाहिए

```csharp
public enum FontEmbeddingOptions
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| NotEmbed | `0` | EditableDocument या सिस्टम से कोई भी फ़ॉन्ट संसाधन एम्बेड न करें। डिफ़ॉल्ट मान। |
| EmbedAll | `1` | इनपुट EditableDocument से दस्तावेज़ सामग्री का विश्लेषण करें, सभी उपयोग किए गए फ़ॉन्ट्स खोजें और उन्हें आउटपुट WordProcessing या PDF दस्तावेज़ में एम्बेड करें। पहले चरण में GroupDocs.Editor EditableDocument के भीतर फ़ॉन्ट संसाधनों से फ़ॉन्ट लेता है। यदि वे अपर्याप्त या अनुपलब्ध हैं, तो GroupDocs.Editor OS से फ़ॉन्ट लेता है। |
| EmbedWithoutSystem | `2` | EmbedAll के समान, लेकिन उन फ़ॉन्ट्स को बाहर रखें, जिन्हें OS सिस्टम फ़ॉन्ट्स के रूप में मानता है। |

### टिप्पणियाँ

फ़ॉन्ट एम्बेडिंग विकल्प दस्तावेज़ सहेजने के दौरान लागू होते हैं (इंटरमीडिएट EditableDocument से आउटपुट WordProcessing या PDF फ़ॉर्मेट में), यह enum WordProcessingSaveOptions और PdfSaveOptions में एक प्रॉपर्टी के रूप में शामिल है, जहाँ से इसे उपयोग किया जाना चाहिए।

### संबंधित देखें

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
