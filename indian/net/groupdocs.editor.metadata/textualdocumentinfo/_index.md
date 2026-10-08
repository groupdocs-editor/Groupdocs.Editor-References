---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक टेक्स्टुअल दस्तावेज़ जैसे XML HTML या सादा पाठ TXT का मेटाडेटा दर्शाता है"
type: docs
weight: 780
url: /hi/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

XML, HTML या साधारण पाठ (TXT) जैसे एक पाठ्य दस्तावेज़ के मेटाडेटा का प्रतिनिधित्व करता है

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | टेक्स्ट दस्तावेज़ की पता लगी अनुमानित एन्कोडिंग लौटाता है |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | इस पाठ्य दस्तावेज़ का फ़ॉर्मेट लौटाता है। कुछ मामलों में यह 100% सही नहीं हो सकता। |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | हमेशा ``false`` लौटाता है, क्योंकि पाठ्य दस्तावेज़ एन्क्रिप्ट नहीं किए जा सकते। |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | हमेशा 1 लौटाता है। |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | इस पाठ्य दस्तावेज़ का आकार बाइट्स में लौटाता है (अक्षरों की संख्या नहीं)। |

### संबंधित देखें

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
