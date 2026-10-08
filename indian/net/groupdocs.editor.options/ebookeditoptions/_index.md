---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी समर्थित फ़ॉर्मेट्स ePub, MOBI और AZW3 में ईबुक दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट और समायोजित करने की अनुमति देता है।"
type: docs
weight: 830
url: /hi/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

सभी समर्थित फॉर्मेट्स: ePub, MOBI, और AZW3 में ई-बुक दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने और समायोजित करने की अनुमति देता है।

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | [`EbookEditOptions`](../ebookeditoptions) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं। |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | [`EbookEditOptions`](../ebookeditoptions) क्लास का एक नया उदाहरण निर्दिष्ट पेजिनेशन मोड के साथ इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | निर्दिष्ट करता है कि भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट के रूप में निर्यात किया जाए या नहीं। यह विकल्प बहु‑भाषी दस्तावेज़ों के राउंड‑ट्रिप रूपांतरण के लिए उपयोगी हो सकता है। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है। |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है। |

### टिप्पणियाँ

समर्थित ई‑बुक फ़ॉर्मेट:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (इलेक्ट्रॉनिक पब्लिकेशन)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
