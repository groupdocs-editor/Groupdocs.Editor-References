---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "किसी भी समर्थित ईमेल प्रारूप के एक ईमेल दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है"
type: docs
weight: 720
url: /hi/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

किसी भी समर्थित ईमेल प्रारूप के एक ईमेल दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | इस ईमेल दस्तावेज़ का फ़ॉर्मेट लौटाता है |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | क्योंकि ईमेल दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह प्रॉपर्टी हमेशा 'false' लौटाती है |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | हमेशा 1 लौटाता है, क्योंकि ईमेल दस्तावेज़ में पेज़्ड व्यू नहीं होता |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | इस ईमेल दस्तावेज़ का आकार बाइट्स में लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अन्य EmailDocumentInfo इंस्टेंस के बराबर है या नहीं |

### संबंधित देखें

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
