---
title: FixedLayoutFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: सभ फक्स्डलेआउट फक्स्डपेज के रूप में भ जन जत है प्ररूपं क समहत करत है जसमें पडएफ और एक्सपएस शमल हैं इसमें रेखपुंज छवयं शमल नहं हैं
type: docs
weight: 80
url: /hi/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

सभी फिक्स्ड-लेआउट ("फिक्स्ड-पेज" के रूप में भी जाना जाता है) प्रारूपों को समाहित करता है, जिसमें पीडीएफ और एक्सपीएस शामिल हैं (इसमें रेखापुंज छवियां शामिल नहीं हैं)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | लोअर केस में इस फिक्स्ड-लेआउट फॉर्मेट का एक्सटेंशन (बिना डॉट कैरेक्टर के) लौटाता है |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | इस प्रारूप के लिए एक MIME कोड लौटाता है |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | इस निश्चित लेआउट प्रारूप का औपचारिक पूरा नाम देता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | का उदाहरण देता है[`FixedLayoutFormats`](../fixedlayoutformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट फिक्स्ड लेआउटफॉर्मैट्स उदाहरण के बराबर है |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट वस्तु के बराबर है, जो संभवतः बॉक्सिंग फिक्स्ड लेआउटफॉर्मैट्स के बराबर है |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | इस विशेष प्रारूप का नाम लौटाता है, 'नाम' गुण के समान |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | समानता पर दिए गए दो फिक्स्डलेआउटफॉर्मैट उदाहरणों की जांच करता है |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | निर्दिष्ट फिक्स्ड लेआउटफॉर्मैट्स उदाहरण के अंतर्निहित क्षेत्र से एक बाइट मान देता है (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | असमानता पर दिए गए दो FixedLayoutFormats उदाहरणों की जाँच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | पोर्टेबल डॉक्यूमेंट फॉर्मेट (पीडीएफ) 1990 के दशक में एडोब द्वारा बनाया गया एक प्रकार का दस्तावेज है। इस फ़ाइल प्रारूप का उद्देश्य एक ऐसे प्रारूप में दस्तावेज़ों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक मानक पेश करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और साथ ही ऑपरेटिंग सिस्टम से स्वतंत्र है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों का प्रतिनिधित्व करती है जो Microsoft द्वारा बनाए गए XML पेपर विनिर्देशों पर आधारित हैं। इसे EMF फ़ाइल स्वरूप के प्रतिस्थापन के रूप में विकसित किया गया था और यह PDF फ़ाइल प्रारूप के समान है, लेकिन दस्तावेज़ के लेआउट, रूप और मुद्रण जानकारी में XML का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा निश्चित-लेआउट स्वरूपों पर असंख्य संभावनाएं प्रदान करता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | IEnumerable जेनेरिक इंटरफ़ेस लागू करता है, जो FixedLayoutFormats type के लिए 'foreach' संभावना को सक्षम करता है |

### टिप्पणियों

विभिन्न दस्तावेज़ देखने या प्रकाशित करने वाले एप्लिकेशन उपयोगकर्ताओं को (Adobe Acrobat, XPS Viewer) खोलने और कभी-कभी विशिष्ट स्वरूपों के दस्तावेज़ों (Adobe InDesign) को संपादित करने की अनुमति देते हैं। ये एप्लिकेशन आमतौर पर तथाकथित "फिक्स्ड-पेज" प्रारूप दस्तावेज़ तैयार करते हैं। इस तरह का एक दस्तावेज़ प्रारूप सटीक रूप से वर्णन करता है कि प्रत्येक पृष्ठ पर दस्तावेज़ की सामग्री कहाँ रखी गई है। आंतरिक रूप से, पीडीएफ या एक्सपीएस प्रारूप में पृष्ठ पर सामग्री के लेआउट को निर्दिष्ट करते हुए प्रत्येक पृष्ठ का विवरण, साथ ही ड्राइंग निर्देश शामिल हैं। यह छवि प्रारूपों के समान है, यह वर्णन करता है कि सामग्री को रेखापुंज या वेक्टर रूप में कहाँ दिखाया गया है।

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
