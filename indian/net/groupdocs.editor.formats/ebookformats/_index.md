---
title: "EBookFormats"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी eBook फ़ॉर्मेट को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3।"
type: docs
weight: 80
url: /hi/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

सभी eBook फ़ॉर्मेट को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | सभी [`EBookFormats`](../ebookformats) का एक enumerable संग्रह प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन वाला निर्दिष्ट प्रकार [`EBookFormats`](../ebookformats) का एक उदाहरण प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`EBookFormats`](../ebookformats) ऑब्जेक्ट में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, जिसे Kindle Format 8 (KF8) भी कहा जाता है, Amazon Kindle डिवाइसों के लिए विकसित AZW ईबुक डिजिटल फ़ाइल फ़ॉर्मेट का संशोधित संस्करण है। यह फ़ॉर्मेट पुराने AZW फ़ाइलों में सुधार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Electronic Publication (IDPF ePub) फ़ॉर्मेट एक e‑book फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI वह फ़ॉर्मेट है जो MobiPocket Reader के लिए विकसित किया गया था। इसे PRC, AZW भी कहा जाता है। यह वर्तमान में Amazon द्वारा थोड़ा अलग DRM स्कीम के साथ उपयोग किया जाता है और इसे AZW कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/mobi/). |

### टिप्पणियाँ

Mobi फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/mobi/), AZW3 फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/azw3/), और ePub फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/epub/).

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
