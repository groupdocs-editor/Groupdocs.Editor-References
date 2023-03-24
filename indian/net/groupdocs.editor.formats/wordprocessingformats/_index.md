---
title: WordProcessingFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: सभ वर्ड प्रसेसंग प्ररूपं क समहत करत है नम्न फ़इल प्रकर शमल हैं Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . वर्ड प्रसेसंग प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /hi/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

सभी वर्ड प्रोसेसिंग प्रारूपों को समाहित करता है। निम्न फ़ाइल प्रकार शामिल हैं: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . वर्ड प्रोसेसिंग प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | लोअर केस में इस वर्डप्रोसेसिंग प्रारूप का एक एक्सटेंशन (अग्रणी डॉट वर्ण के बिना) देता है |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | इस प्रारूप के लिए एक MIME कोड लौटाता है |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | इस वर्डप्रोसेसिंग प्रारूप का औपचारिक पूरा नाम लौटाता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | का उदाहरण देता है[`WordProcessingFormats`](../wordprocessingformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट ऑब्जेक्ट के बराबर है, जो संभवतः बॉक्सिंग वाले WordProcessingFormats के बराबर है |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट WordProcessingFormats उदाहरण के बराबर है |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | इस विशेष प्रारूप का नाम लौटाता है, 'नाम' गुण के समान |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | समानता पर दिए गए दो WordProcessingFormats उदाहरणों की जाँच करता है |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | निर्दिष्ट WordProcessingFormats उदाहरण के अंतर्निहित फ़ील्ड से एक बाइट मान लौटाता है (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | असमानता पर दिए गए WordProcessingFormats के दो उदाहरणों की जाँच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | एमएस वर्ड 97-2007 बाइनरी फाइल फॉर्मेट (डीओसी) माइक्रोसॉफ्ट वर्ड या बाइनरी फाइल फॉर्मेट में अन्य वर्ड प्रोसेसिंग दस्तावेजों द्वारा उत्पन्न दस्तावेजों का प्रतिनिधित्व करता है। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML मैक्रो-सक्षम दस्तावेज़ (DOCM) फ़ाइलें Microsoft Word 2007 या मैक्रोज़ चलाने की क्षमता के साथ उच्चतर जनरेट किए गए दस्तावेज़ हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | ऑफिस ओपन एक्सएमएल वर्ड प्रोसेसिंगएमएल मैक्रो-फ्री डॉक्यूमेंट (DOCX) माइक्रोसॉफ्ट वर्ड दस्तावेजों के लिए एक प्रसिद्ध प्रारूप है। Microsoft Office 2007 की रिलीज़ के साथ 2007 से पेश किया गया, इस नए दस्तावेज़ प्रारूप की संरचना को सादे बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दिया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | एमएस वर्ड 97-2007 टेम्प्लेट माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फाइलें हैं, जो आगे डीओसी या डीओसीएक्स फाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | ऑफिस ओपन एक्सएमएल वर्ड प्रोसेसिंगएमएल मैक्रो-सक्षम टेम्पलेट (डीओटीएम) माइक्रोसॉफ्ट वर्ड 2007 या उच्चतर के साथ बनाई गई टेम्पलेट फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल मैक्रो-फ्री टेम्प्लेट (डीओटीएक्स) माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फाइलें हैं, जो आगे की डीओसीएक्स फाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल एक ज़िप पैकेज के बजाय एक फ्लैट एक्सएमएल फ़ाइल में संग्रहीत |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | ओपन डॉक्यूमेंट फॉर्मेट टेक्स्ट डॉक्यूमेंट (ODT) फाइलें वर्ड प्रोसेसिंग एप्लिकेशन के साथ बनाए गए दस्तावेजों के प्रकार हैं जो OpenDocument टेक्स्ट फाइल फॉर्मेट पर आधारित हैं। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | ओपन डॉक्यूमेंट फॉर्मेट टेक्स्ट डॉक्यूमेंट टेम्प्लेट (OTT) OASIS के OpenDocument मानक प्रारूप के अनुपालन में एप्लिकेशन द्वारा उत्पन्न टेम्प्लेट दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | रिच टेक्स्ट फ़ॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए स्वरूपित टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML स्वरूप — WordProcessingML या WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा WordProcessing स्वरूपों पर असंख्य संभावनाएं प्रदान करता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | IEnumerable जेनेरिक इंटरफ़ेस लागू करता है, जो WordProcessingFormats type के लिए 'foreach' संभावना को सक्षम करता है |

### टिप्पणियों

MIME कोड दिए गए संसाधनों से लिए गए हैं: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
