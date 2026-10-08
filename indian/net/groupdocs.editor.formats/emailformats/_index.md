---
title: "EmailFormats"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी ईमेल फ़ॉर्मेट को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /hi/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

सभी ईमेल फ़ॉर्मेट को सम्मिलित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | सभी [`EmailFormats`](../emailformats) का एक enumerable संग्रह प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | निर्दिष्ट फ़ाइल एक्सटेंशन वाला निर्दिष्ट प्रकार [`EmailFormats`](../emailformats) का एक उदाहरण प्राप्त करता है। |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`EmailFormats`](../emailformats) ऑब्जेक्ट में परिवर्तित करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML फ़ाइल फ़ॉर्मेट Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML स्वरूपित ईमेल। |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) एक इंटरनेट मानक (RFC 2445) है जो कैलेंडर इवेंट्स और शेड्यूलिंग के आदान‑प्रदान और तैनाती के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox फ़ाइल फ़ॉर्मेट एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के कंटेनर को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, "MIME encapsulation of aggregate HTML documents" का संक्षिप्त रूप है। |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG एक फ़ाइल फ़ॉर्मेट है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft एक्सटेंशन वाली फ़ाइलें टेम्पलेट फ़ाइलें हैं जो Microsoft Outlook का उपयोग करके बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | ऑफ़लाइन स्टोरेज टेबल (OST) फ़ाइल उपयोगकर्ता के मेलबॉक्स डेटा को ऑफ़लाइन मोड में स्थानीय मशीन पर Exchange Server के साथ पंजीकरण के बाद Microsoft Outlook का उपयोग करके दर्शाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/ost/) देखें। |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst एक्सटेंशन वाली फ़ाइलें Outlook पर्सनल स्टोरेज फ़ाइलें (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) को दर्शाती हैं जो उपयोगकर्ता की विभिन्न जानकारी संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/pst/) देखें। |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | ट्रांसपोर्ट न्यूट्रल एन्कैप्सुलेशन फ़ॉर्मेट (TNEF) Microsoft का स्वामित्व वाला फ़ॉर्मेट है जो मैसेजिंग एप्लिकेशन प्रोग्रामिंग इंटरफ़ेस (MAPI) के आधार पर ईमेल अटैचमेंट्स को एन्कैप्सुलेट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/tnef/) देखें। |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (वर्चुअल कार्ड फ़ॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/vcf/) देखें। |

### टिप्पणियाँ

ईमेल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/) देखें।

### संबंधित देखें

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
