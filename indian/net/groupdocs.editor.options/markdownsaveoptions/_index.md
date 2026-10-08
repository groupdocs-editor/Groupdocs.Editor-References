---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Markdown दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1000
url: /hi/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

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
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | निर्धारित करता है कि छवियों को आउटपुट फ़ाइल में Base64 फ़ॉर्मेट में सहेजा जाए या नहीं। डिफ़ॉल्ट `false` है। |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | निर्धारित करता है कि मार्कडाउन फ़ॉर्मेट में दस्तावेज़ निर्यात करते समय छवियों को किस फ़ोल्डर में सहेजा जाए। डिफ़ॉल्ट `null` है। |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | HTML से दस्तावेज़ जनरेशन के दौरान मेमोरी अनुकूलन तंत्र सक्षम करता है, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है। इस विकल्प को `true` पर सेट करने से बड़े दस्तावेज़ उत्पन्न करते समय मेमोरी खपत काफी घट सकती है, लेकिन सहेजने का समय धीमा हो जाता है। डिफ़ॉल्ट `false` है (बेहतर प्रदर्शन के लिए मेमोरी अनुकूलन अक्षम है)। |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | मार्कडाउन फ़ॉर्मेट में निर्यात करते समय तालिकाओं में सामग्री को कैसे संरेखित किया जाए, यह निर्दिष्ट करता है। डिफ़ॉल्ट मान Auto है। |

### टिप्पणियाँ

MarkdownSaveOptions क्लास को उपयोगकर्ता द्वारा लागू किया जाना चाहिए जब EditableDocument क्लास का एक इंस्टेंस मौजूद हो, जिसमें संपादित दस्तावेज़ सामग्री हो, और इस सामग्री को मार्कडाउन फ़ॉर्मेट के नए दस्तावेज़ में सहेजना आवश्यक हो।

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
