---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी फ़ाइल मेटाडेटा रैपर के लिए सामान्य इंटरफ़ेस"
type: docs
weight: 740
url: /hi/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

सभी फ़ाइल मेटाडेटा रैपर के लिए सामान्य इंटरफ़ेस

```csharp
public interface IDocumentInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | इम्प्लीमेंट करने वाले प्रकार को एक दस्तावेज़ फ़ॉर्मेट एकल मान के रूप में लौटाना चाहिए, जो एक फ़ॉर्मेट परिवार का प्रतिनिधित्व करता है और IDocumentFormat इंटरफ़ेस से विरासत में मिलता है। |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | यह दर्शाता है कि विशिष्ट फ़ाइल एन्क्रिप्टेड है और खोलने के लिए पासवर्ड की आवश्यकता है या नहीं। उन दस्तावेज़ प्रकारों के लिए, जिन्हें एन्क्रिप्ट नहीं किया जा सकता (जैसे सभी टेक्स्ट-आधारित), हमेशा 'false' लौटाना चाहिए। |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | इम्प्लीमेंट करने वाले प्रकार को पृष्ठों या अन्य समान फ़ॉर्मेट-निर्भर इकाइयों (टैब, स्लाइड आदि) की गिनती (संख्या) लौटानी चाहिए। उन परिवार प्रकारों के लिए, जिनमें ऐसी कोई समान इकाई नहीं है (जैसे सादा टेक्स्ट दस्तावेज़ या XML), 1 लौटाना चाहिए। |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | दस्तावेज़ का आकार बाइट्स में |

### संबंधित देखें

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
