---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "PDF जैसे fixedlayout fixedpage दस्तावेज़ फ़ॉर्मेट को दर्शाता है, जिसमें रास्टर इमेज फ़ॉर्मेट शामिल नहीं हैं।"
type: docs
weight: 100
url: /hi/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

स्थिर-लेआउट (स्थिर-पृष्ठ) दस्तावेज़ फ़ॉर्मेट का प्रतिनिधित्व करता है, जैसे PDF, रास्टर इमेज फ़ॉर्मेट को छोड़कर।

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | [`FixedLayoutFormats`](../fixedlayoutformats) के सभी उपलब्ध उदाहरण प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन से मेल खाने वाला एक [`FixedLayoutFormats`](../fixedlayoutformats) उदाहरण पुनः प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | फ़ाइल एक्सटेंशन स्ट्रिंग को स्पष्ट रूप से एक [`FixedLayoutFormats`](../fixedlayoutformats) उदाहरण में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Adobe द्वारा प्रस्तुत पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट (PDF), सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र रूप से दस्तावेज़ों का मानकीकृत प्रतिनिधित्व प्रदान करता है। अतिरिक्त विवरण के लिए देखें: [PDF फ़ाइल फ़ॉर्मेट](https://docs.fileformat.com/pdf/)। |

### टिप्पणियाँ

Fixed-layout फ़ॉर्मेट प्रत्येक पृष्ठ पर सामग्री की स्थिति और रेंडरिंग को सटीक रूप से निर्धारित करते हैं। ये आमतौर पर Adobe Acrobat और Adobe InDesign जैसे दस्तावेज़ देखना, प्रकाशन या संपादन अनुप्रयोगों में उपयोग होते हैं। ये फ़ॉर्मेट आंतरिक रूप से वेक्टर ग्राफ़िक्स और टेक्स्ट निर्देशों का उपयोग करके पृष्ठ लेआउट और सामग्री की स्थिति को परिभाषित करते हैं।

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
