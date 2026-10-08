---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक WordProcessing दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है"
type: docs
weight: 790
url: /hi/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

एक WordProcessing दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | इस वर्डप्रोसेसिंग दस्तावेज़ का फ़ॉर्मेट लौटाता है |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | निर्धारित करता है कि यह विशिष्ट वर्डप्रोसेसिंग दस्तावेज़ एन्क्रिप्टेड है और खोलने के लिए पासवर्ड आवश्यक है या नहीं |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | पृष्ठों की संख्या लौटाता है |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | इस वर्डप्रोसेसिंग दस्तावेज़ का आकार बाइट्स में लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अन्य WordProcessingDocumentInfo इंस्टेंस के बराबर है या नहीं |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | चयनित पृष्ठ का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है |

### संबंधित देखें

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
