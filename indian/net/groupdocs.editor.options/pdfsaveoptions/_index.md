---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "PDF पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 1070
url: /hi/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

PDF (Portable Document Format) दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | आउटपुट दस्तावेज़ों के लिए PDF मानकों के अनुपालन स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट है PdfCompliance.Pdf17। |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | मूल दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को परिणामी PDF दस्तावेज़ में एम्बेड करने के लिए ज़िम्मेदार है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)। |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी ऑप्टिमाइज़ेशन मैकेनिज़्म सक्षम करता है, जो मेमोरी उपयोग कम करने की कीमत पर प्रदर्शन को घटाता है। इस विकल्प को true सेट करने से बड़े दस्तावेज़ जनरेट करते समय मेमोरी खपत में काफी कमी आ सकती है, लेकिन सहेजने के समय धीमा हो जाता है। डिफ़ॉल्ट रूप से false है (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है)। |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | पासवर्ड, जो उत्पन्न PDF दस्तावेज़ पर उपयोगकर्ता पासवर्ड के रूप में लागू होगा, खोलने के लिए आवश्यक है। यदि NULL या खाली है, तो दस्तावेज़ पर कोई पासवर्ड लागू नहीं होगा। अन्यथा, दस्तावेज़ RC4 (128 बिट कुंजी लंबाई) से एन्क्रिप्ट किया जाएगा। डिफ़ॉल्ट रूप से NULL है — पासवर्ड लागू नहीं होता। |

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
