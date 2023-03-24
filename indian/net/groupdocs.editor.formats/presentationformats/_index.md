---
title: PresentationFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: सभ प्रस्तुत स्वरूपं क समहत करत है नम्नलखत प्ररूप शमल हैं Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. प्रस्तुत प्ररूपं के बरे में और जनेंयहँhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /hi/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

सभी प्रस्तुति स्वरूपों को समाहित करता है। निम्नलिखित प्रारूप शामिल हैं: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). प्रस्तुति प्रारूपों के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | लोअर केस में इस प्रेजेंटेशन फॉर्मेट का एक्सटेंशन (बिना डॉट कैरेक्टर के) लौटाता है |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | इस प्रारूप के लिए एक MIME कोड लौटाता है |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | इस प्रस्तुति प्रारूप का औपचारिक पूरा नाम लौटाता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | का उदाहरण देता है[`PresentationFormats`](../presentationformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट वस्तु के बराबर है, जो संभवतः बॉक्सिंग प्रेजेंटेशनफॉर्मैट्स के बराबर है |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट प्रस्तुतिकरण उदाहरण के बराबर है |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | समानता पर दिए गए दो प्रेजेंटेशनफॉर्मैट उदाहरणों की जांच करता है |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | असमानता पर दिए गए दो प्रेजेंटेशनफॉर्मेट उदाहरणों की जांच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument प्रस्तुति (ODP) फ़ाइल OASISOpen मानक में OpenOffice.org द्वारा प्रयुक्त प्रस्तुति फ़ाइल प्रारूप का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument प्रस्तुति टेम्पलेट (OTP) फ़ाइल OASIS OpenDocument मानक प्रारूप में एप्लिकेशन द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 प्रस्तुति टेम्पलेट (POT) फ़ाइल PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | माइक्रोसॉफ्ट ऑफिस ओपन एक्सएमएल प्रस्तुतिएमएल मैक्रो-सक्षम टेम्पलेट (पीओटीएम) मैक्रोज़ के समर्थन वाली फाइलें हैं। POTM फाइलें PowerPoint 2007 या इसके बाद के संस्करण के साथ बनाई गई हैं और इसमें डिफ़ॉल्ट सेटिंग्स हैं जिनका उपयोग आगे की प्रस्तुति फ़ाइलों को बनाने के लिए किया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | माइक्रोसॉफ्ट ऑफिस ओपन एक्सएमएल प्रस्तुतिएमएल मैक्रो-फ्री टेम्पलेट (पीओटीएक्स) फ़ाइल माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रस्तुतियों का प्रतिनिधित्व करती है जो माइक्रोसॉफ्ट पावरपॉइंट 2007 और इसके बाद के संस्करण के साथ बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 स्लाइडशो (PPS) फ़ाइलें स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | माइक्रोसॉफ्ट ऑफिस ओपन एक्सएमएल प्रस्तुति एमएल मैक्रो-सक्षम स्लाइड शो (पीपीएसएम) फाइलें माइक्रोसॉफ्ट पावरप्वाइंट 2007 या उच्चतर के साथ बनाई गई हैं। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | माइक्रोसॉफ्ट ऑफिस ओपन एक्सएमएल प्रेजेंटेशनएमएल मैक्रो-फ्री स्लाइडशो (पीपीएसएक्स) फ़ाइल स्लाइड शो उद्देश्य के लिए माइक्रोसॉफ्ट पावरपॉइंट 2007 और इसके बाद के संस्करण का उपयोग करके बनाई गई है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint प्रस्तुति (.ppt) PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | माइक्रोसॉफ्ट पॉवरपॉइंट 95 प्रस्तुति (पीपीटी) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML प्रस्तुतिML मैक्रो-सक्षम दस्तावेज़ (PPTM) फ़ाइलें जो Microsoft PowerPoint 2007 या उच्चतर संस्करणों के साथ बनाई गई हैं। वे PPTX फ़ाइलों के समान हैं, इस अंतर के साथ कि पार्श्व मैक्रोज़ को निष्पादित नहीं कर सकते हैं, हालांकि उनमें मैक्रोज़ हो सकते हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | पावरपॉइंट ओपन एक्सएमएल प्रेजेंटेशन (.pptx) एक प्रेजेंटेशन फाइल है जिसे लोकप्रिय माइक्रोसॉफ्ट पॉवरपॉइंट एप्लिकेशन के साथ बनाया गया है। प्रस्तुति फ़ाइल प्रारूप पीपीटी के पिछले संस्करण के विपरीत जो बाइनरी था, पीपीटीएक्स प्रारूप माइक्रोसॉफ्ट पावरपॉइंट ओपन एक्सएमएल प्रस्तुति फ़ाइल प्रारूप पर आधारित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा प्रस्तुति स्वरूपों पर असंख्य संभावनाएं प्रदान करता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | IENumerable जेनेरिक इंटरफ़ेस लागू करता है, जो प्रेजेंटेशनफॉर्मैट्स टाइप के लिए 'foreach' संभावना को सक्षम करता है |

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
