---
title: EmailFormats
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: सभ ईमेल प्ररूपं क समहत करत है नम्न फ़इल प्रकर शमल हैं Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /hi/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

सभी ईमेल प्रारूपों को समाहित करता है। निम्न फ़ाइल प्रकार शामिल हैं: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | कार्यान्वयन प्रकार में प्रारूप फ़ाइल एक्सटेंशन वापस करना चाहिए (अग्रणी डॉट वर्ण के बिना)। |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | कार्यान्वयन प्रकार में दिए गए प्रारूप के लिए एक एमआईएमई-कोड वापस करना चाहिए |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | कार्यान्वयन प्रकार में पूर्ण औपचारिक स्वरूप नाम वापस करना चाहिए |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | का उदाहरण देता है[`EmailFormats`](../emailformats) संरचना, निर्दिष्ट फ़ाइल नाम एक्सटेंशन से संबद्ध, या एक अपवाद फेंकता है, यदि एक्सटेंशन ठीक से पार्स नहीं किया जा सकता है |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट ईमेल उदाहरण के बराबर है |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट IDocumentFormat उदाहरण के बराबर है |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | निर्धारित करता है कि क्या यह उदाहरण अन्य निर्दिष्ट वस्तु के बराबर है, जो संभवतः बॉक्सिंग ईमेल का है |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | एक हैश-कोड देता है, जो इस उदाहरण के लिए अपरिवर्तनीय है |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | इस प्रारूप का एक प्रारूप नाम देता है |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | समानता पर दिए गए दो ईमेल उदाहरणों की जांच करता है |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | असमानता पर दिए गए दो ईमेल उदाहरणों की जांच करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | ईएमएल फ़ाइल प्रारूप आउटलुक और अन्य प्रासंगिक अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX फ़ाइल स्वरूप Apple द्वारा कार्यान्वित और विकसित किया गया है। ईमेल निर्यात करने के लिए Apple मेल एप्लिकेशन EMLX फ़ाइल स्वरूप का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML स्वरूपित ईमेल. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | इंटरनेट कैलेंडरिंग और शेड्यूलिंग कोर ऑब्जेक्ट स्पेसिफिकेशन (iCalendar) कैलेंडरिंग इवेंट्स और शेड्यूलिंग के आदान-प्रदान और तैनाती के लिए एक इंटरनेट मानक (RFC 2445) है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox फ़ाइल स्वरूप एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए एक कंटेनर का प्रतिनिधित्व करता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, "कुल HTML दस्तावेज़ों के MIME एनकैप्सुलेशन" का प्रारंभिक रूप |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG एक फ़ाइल स्वरूप है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेशों, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft एक्सटेंशन वाली फ़ाइलें टेम्प्लेट फ़ाइलें होती हैं जो Microsoft Outlook का उपयोग करके बनाई जाती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | ऑफ़लाइन संग्रहण तालिका (OST) फ़ाइल Microsoft Outlook का उपयोग करके एक्सचेंज सर्वर के साथ पंजीकरण पर स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst एक्सटेंशन वाली फाइलें आउटलुक पर्सनल स्टोरेज फाइल्स (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) का प्रतिनिधित्व करती हैं जो विभिन्न प्रकार की उपयोगकर्ता सूचनाओं को स्टोर करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | ट्रांसपोर्ट न्यूट्रल इनकैप्सुलेशन फॉर्मेट (TNEF) मैसेजिंग एप्लिकेशन प्रोग्रामिंग इंटरफेस (MAPI) पर आधारित ईमेल अटैचमेंट को एनकैप्सुलेट करने के लिए Microsoft का एक स्वामित्व है। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (वर्चुअल कार्ड फॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल स्वरूप है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | एक आंतरिक वर्ग लौटाता है, जो सभी मौजूदा ईमेल प्रारूपों पर असंख्य संभावनाएं प्रदान करता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | IEnumerable जेनेरिक इंटरफ़ेस लागू करता है, जो ईमेल type के लिए 'foreach' संभावना को सक्षम करता है |

### टिप्पणियों

ईमेल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/email/) .

### यह सभी देखें

* interface [IDocumentFormat](../idocumentformat)
* नाम स्थान [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
