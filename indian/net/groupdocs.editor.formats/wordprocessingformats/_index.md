---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी WordProcessing फ़ॉर्मेट्स को समाहित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं"
type: docs
weight: 150
url: /hi/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

सभी वर्डप्रोसेसिंग फ़ॉर्मेट को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Word Processing फ़ॉर्मेट्स के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing) देखें।

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | सभी [`WordProcessingFormats`](../wordprocessingformats) की एक enumerable collection प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार [`WordProcessingFormats`](../wordprocessingformats) का एक instance प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`WordProcessingFormats`](../wordprocessingformats) ऑब्जेक्ट में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 बाइनरी फ़ाइल फ़ॉर्मेट (DOC) माइक्रोसॉफ्ट वर्ड या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा उत्पन्न दस्तावेज़ों को बाइनरी फ़ाइल फ़ॉर्मेट में दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/doc) देखें। |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) फ़ाइलें Microsoft Word 2007 या उससे ऊपर द्वारा उत्पन्न दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docm)। |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) Microsoft Word दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docx)। |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template (DOT) Microsoft Word द्वारा निर्मित टेम्प्लेट फ़ाइलें हैं जो आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स रखती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dot)। |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) Microsoft Word 2007 या उससे ऊपर के साथ निर्मित टेम्प्लेट फ़ाइलों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotm)। |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) Microsoft Word द्वारा निर्मित टेम्प्लेट फ़ाइलें हैं जो आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स रखती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotx)। |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत किया जाता है। |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Text Document (ODT) फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित वर्ड प्रोसेसिंग अनुप्रयोगों से बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/odt)। |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) OASIS के OpenDocument मानक फ़ॉर्मेट के अनुपालन में अनुप्रयोगों द्वारा उत्पन्न टेम्प्लेट दस्तावेज़ों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/ott)। |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) स्वरूपित टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि को दर्शाता है जिसका उपयोग अनुप्रयोगों के भीतर किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/rtf)। |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML फ़ॉर्मेट — WordProcessingML या WordML (.XML)। |

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
