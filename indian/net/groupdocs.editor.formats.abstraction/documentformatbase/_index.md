---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "डॉक्यूमेंट फ़ॉर्मेट्स के लिए बेस क्लास का प्रतिनिधित्व करता है जो फ़ॉर्मेट इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

दस्तावेज़ फ़ॉर्मैट्स के लिए बेस क्लास का प्रतिनिधित्व करता है, जो फ़ॉर्मैट इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | डॉक्यूमेंट फ़ॉर्मेट का फ़ाइल एक्सटेंशन प्राप्त करता है। |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | डॉक्यूमेंट फ़ॉर्मेट जिस फ़ॉर्मेट फैमिली से संबंधित है, उसे प्राप्त करता है। |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`IDocumentFormat`](../idocumentformat) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`DocumentFormatBase`](../documentformatbase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | निर्दिष्ट प्रकार *T* की एक इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट MIME प्रकार है। |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | एक [`DocumentFormatBase`](../documentformatbase) इंस्टेंस को अप्रत्यक्ष रूप से स्ट्रिंग में परिवर्तित करता है। |

### संबंधित देखें

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
