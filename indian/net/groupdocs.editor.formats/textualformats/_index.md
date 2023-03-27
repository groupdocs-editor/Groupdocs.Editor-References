---
title: TextualFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: मर्कअप एक्सएमएल एचटएमएल और अन्य सहत सभ पठ्य पठआधरत प्ररूपं क समहत करत है नम्नलखत प्ररूपं क शमल करत है Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /hi/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

मार्कअप (एक्सएमएल, एचटीएमएल) और अन्य सहित सभी पाठ्य (पाठ-आधारित) प्रारूपों को समाहित करता है। निम्नलिखित प्रारूपों को शामिल करता है: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | लोअर केस में इस शाब्दिक प्रारूप का एक एक्सटेंशन (बिना प्रमुख बिंदु वर्ण के) लौटाता है |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | इस प्रारूप के लिए एक MIME कोड लौटाता है |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | इस शाब्दिक प्रारूप का एक औपचारिक पूरा नाम लौटाता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | का उदाहरण देता है[`TextualFormats`](../textualformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट वस्तु के बराबर है, जो संभवतः बॉक्सिंग टेक्स्टुअलफॉर्मैट्स के बराबर है |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट TextualFormats उदाहरण के बराबर है |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | इस विशेष प्रारूप का नाम लौटाता है, 'नाम' गुण के समान |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | दो दिए गए TextualFormats उदाहरणों को समानता पर चेक करता है |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | असमानता पर दो दिए गए TextualFormats उदाहरणों की जाँच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft संकलित HTML मदद एक Microsoft स्वामित्व वाली ऑनलाइन मदद बाइनरी प्रारूप है, जिसमें HTML पृष्ठों का संग्रह, एक अनुक्रमणिका और अन्य नेविगेशन उपकरण शामिल हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | हाइपरटेक्स्ट मार्कअप लैंग्वेज डॉक्यूमेंट (एचटीएमएल) ब्राउज़रों में प्रदर्शन के लिए बनाए गए वेब पेजों का विस्तार है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (जावास्क्रिप्ट ऑब्जेक्ट नोटेशन) डेटा साझा करने के लिए एक खुला मानक फ़ाइल स्वरूप है जो डेटा को संग्रहीत और प्रसारित करने के लिए मानव-पठनीय पाठ का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | मार्कडाउन एक सादा-पाठ संपादक का उपयोग करके स्वरूपित पाठ बनाने के लिए एक हल्की मार्कअप भाषा है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | समग्र HTML दस्तावेज़ों का MIME एनकैप्सुलेशन एक वेब पेज संग्रह प्रारूप है, जिसका उपयोग एक कंप्यूटर फ़ाइल में, HTML कोड और उसके सहयोगी संसाधनों को संयोजित करने के लिए किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | सादा पाठ दस्तावेज़ (TXT) एक पाठ दस्तावेज़ का प्रतिनिधित्व करता है जिसमें पंक्तियों के रूप में सादा पाठ होता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | एक्स्टेंसिबल मार्कअप लैंग्वेज डॉक्यूमेंट (XML) जो HTML के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग का उपयोग करने में भिन्न है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा टेक्स्ट प्रारूपों पर असंख्य संभावनाएं प्रदान करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | IEnumerable जेनेरिक इंटरफ़ेस लागू करता है, जो TextualFormats type के लिए 'foreach' संभावना को सक्षम करता है |

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
