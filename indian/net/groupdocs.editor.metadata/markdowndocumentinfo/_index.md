---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक Markdown दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है"
type: docs
weight: 750
url: /hi/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

एक Markdown दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | इस मार्कडाउन दस्तावेज़ का फ़ॉर्मेट लौटाता है — हमेशा [`Md`](../../groupdocs.editor.formats/textualformats/md) होता है। |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | क्योंकि मार्कडाउन दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह प्रॉपर्टी हमेशा ``false`` लौटाती है। |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | पृष्ठों की संख्या लौटाता है। मार्कडाउन दस्तावेज़ आमतौर पर स्थिर पृष्ठ नहीं रखते, इसलिए पृष्ठ गिनती नहीं होती; यह संख्या मानक पृष्ठ आकार A4 पोर्ट्रेट अभिविन्यास से गणना की जाती है। |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | इस मार्कडाउन दस्तावेज़ का आकार बाइट्स में लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अन्य [`MarkdownDocumentInfo`](../markdowndocumentinfo) इंस्टेंस के बराबर है या नहीं। |

### संबंधित देखें

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
