---
title: MarkdownSaveOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: मर्कडउन दस्तवेज़ बनने और सहेजने के लए कस्टम वकल्प नर्दष्ट करने क अनुमत देत है
type: docs
weight: 990
url: /hi/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

मार्कडाउन दस्तावेज़ बनाने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | निर्दिष्ट करता है कि छवियों को आउटपुट फ़ाइल में बेस64 प्रारूप में सहेजा गया है या नहीं। डिफ़ॉल्ट है`असत्य` . |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | उस भौतिक फ़ोल्डर को निर्दिष्ट करता है जहां मार्कडाउन प्रारूप में दस्तावेज़ निर्यात करते समय छवियों को सहेजा जाता है। डिफ़ॉल्ट शून्य है। |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | HTML से दस्तावेज़ निर्माण के दौरान मेमोरी ऑप्टिमाइज़ेशन तंत्र को सक्षम करता है, जो स्मृति उपयोग को कम करने की लागत के रूप में प्रदर्शन को कम करता है। इस विकल्प को सेट करना`सत्य`धीमी बचत समय की कीमत पर बड़े दस्तावेज़ बनाते समय स्मृति खपत में काफी कमी आ सकती है। डिफ़ॉल्ट है`असत्य` (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | अनुमति निर्दिष्ट करती है कि मार्कडाउन प्रारूप में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित करें। डिफ़ॉल्ट मान हैAuto . |

### टिप्पणियों

MarkdownSaveOptions वर्ग को उपयोगकर्ता द्वारा लागू किया जाना चाहिए जब संपादन योग्य दस्तावेज़ वर्ग का एक उदाहरण होता है, जिसमें एक संपादित दस्तावेज़ सामग्री होती है, और इस सामग्री को मार्कडाउन प्रारूप के नए दस्तावेज़ में सहेजना आवश्यक होता है।

### यह सभी देखें

* interface [ISaveOptions](../isaveoptions)
* नाम स्थान [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
