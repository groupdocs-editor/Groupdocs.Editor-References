---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक ईबुक दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है"
type: docs
weight: 710
url: /hi/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

एक e-Book दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | इस ई-बुक का फ़ॉर्मेट लौटाता है |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | क्योंकि ई-बुक दस्तावेज़ पासवर्ड से एन्क्रिप्ट नहीं किए जा सकते, यह प्रॉपर्टी हमेशा 'false' लौटाती है |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | MOBI या AZW3 के मामले में पृष्ठों की संख्या या ePub के मामले में अध्यायों की संख्या लौटाता है। |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | इस eBook दस्तावेज़ का आकार बाइट्स में लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट EbookDocumentInfo इंस्टेंस के बराबर है या नहीं। |

### संबंधित देखें

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
