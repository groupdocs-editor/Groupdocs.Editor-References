---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी समर्थित eBook फ़ॉर्मेट्स ePub, MOBI और AZW3 में दस्तावेज़ को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 840
url: /hi/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

सभी समर्थित ई-बुक फॉर्मेट्स: ePub, MOBI, और AZW3 में दस्तावेज़ को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | यह पैरामीटरलेस कंस्ट्रक्टर EbookSaveOptions की नई instance बनाता है ePub आउटपुट फ़ॉर्मेट के साथ (फिर इसे [`OutputFormat`](./outputformat) प्रॉपर्टी के माध्यम से संशोधित किया जा सकता है)। |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | निर्दिष्ट अनिवार्य e-Book आउटपुट फ़ॉर्मेट के साथ एक नया [`EbookSaveOptions`](../ebooksaveoptions) इंस्टेंस बनाता है, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट होते हैं |

## गुण

| नाम | विवरण |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | निर्धारित करता है कि परिणामस्वरूप फ़ाइल में बिल्ट‑इन और कस्टम दस्तावेज़ प्रॉपर्टी निर्यात की जाएँ या नहीं। डिफ़ॉल्ट मान `false` है। |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | परिणामस्वरूप e-Book फ़ाइल का फ़ॉर्मेट निर्दिष्ट करता है: IDPF ePub, MOBI, या AZW3। |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान `2` है। इसे `0` पर सेट करने से विभाजन निष्क्रिय हो जाएगा, इसलिए e-Book की सभी सामग्री एक ही पैकेज में सम्मिलित हो जाएगी जो परिणामस्वरूप फ़ाइल में होगी। |

### टिप्पणियाँ

समर्थित ई‑बुक फ़ॉर्मेट:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (इलेक्ट्रॉनिक पब्लिकेशन)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
