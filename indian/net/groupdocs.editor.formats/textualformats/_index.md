---
title: "TextualFormats"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी टेक्स्टुअल टेक्स्ट-आधारित फ़ॉर्मेट्स को सम्मिलित करता है जिसमें मार्कअप XML HTML और अन्य शामिल हैं। निम्नलिखित फ़ॉर्मेट्स शामिल हैं Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /hi/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

सभी टेक्स्टुअल (टेक्स्ट-आधारित) फ़ॉर्मेट्स को सम्मिलित करता है, जिसमें मार्कअप (XML, HTML) और अन्य शामिल हैं। निम्नलिखित फ़ॉर्मेट्स शामिल हैं: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | सभी [`TextualFormats`](../textualformats) की एक इटेरेबल कलेक्शन प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [`TextualFormats`](../textualformats) का एक इंस्टेंस पुनः प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`TextualFormats`](../textualformats) ऑब्जेक्ट में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help एक Microsoft स्वामित्व वाला ऑनलाइन हेल्प बाइनरी फ़ॉर्मेट है, जिसमें HTML पृष्ठों का संग्रह, एक इंडेक्स और अन्य नेविगेशन टूल्स शामिल हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language दस्तावेज़ (HTML) वेब पेजों के लिए एक्सटेंशन है जो ब्राउज़र में प्रदर्शित होने के लिए बनाए गए हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) डेटा साझा करने के लिए एक ओपन स्टैंडर्ड फ़ाइल फ़ॉर्मेट है जो मानव-पठनीय टेक्स्ट का उपयोग करके डेटा को संग्रहीत और प्रसारित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown एक हल्की मार्कअप भाषा है जो साधारण टेक्स्ट एडिटर का उपयोग करके स्वरूपित टेक्स्ट बनाने के लिए प्रयोग की जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME एन्कैप्सुलेशन ऑफ एग्रीगेट HTML डॉक्यूमेंट्स एक वेब पेज आर्काइव फ़ॉर्मेट है जो एक ही कंप्यूटर फ़ाइल में HTML कोड और उसके सहयोगी संसाधनों को संयोजित करने के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) एक टेक्स्ट दस्तावेज़ है जिसमें पंक्तियों के रूप में साधारण टेक्स्ट होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language दस्तावेज़ (XML) जो HTML के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग का उपयोग करने में अलग है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/web/xml)। |

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
