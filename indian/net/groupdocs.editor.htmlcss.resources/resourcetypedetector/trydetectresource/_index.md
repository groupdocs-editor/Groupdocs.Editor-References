---
title: "TryDetectResource"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इनपुट स्ट्रीम का विश्लेषण करने का प्रयास करता है और यदि निर्दिष्ट अनुमानित प्रकार null नहीं है तो उसे ध्यान में रखते हुए उससे समर्थित HTML संसाधनों में से एक बनाता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

इनपुट स्ट्रीम का विश्लेषण करने का प्रयास करता है और उससे समर्थित HTML संसाधनों में से एक बनाता है, निर्दिष्ट अनुमानित प्रकार को ध्यान में रखते हुए, यदि वह null न हो

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| inputResourceStream | Stream | इनपुट स्ट्रीम, जिसमें संभवतः एक HTML संसाधन होता है। यदि अमान्य है, तो एक अपवाद फेंका जाएगा। |
| name | String | संसाधन नाम, जिसका उपयोग सफल होने पर बनाए गए और लौटाए गए संसाधन के लिए किया जाएगा। यह NULL, खाली या whitespace नहीं हो सकता। |
| assumptiveFormat | IResourceType | इनपुट HTML संसाधन का अनुमानित फ़ॉर्मेट, जो सर्वोत्तम प्रदर्शन प्राप्त करने में उपयोगी है। यदि पूरी तरह अज्ञात हो, तो NULL मान का उपयोग करें। यह गलत भी हो सकता है, इससे केवल प्रदर्शन बिगड़ेगा। |

### रिटर्न मान

इंस्टेंस, जो 'IHtmlResource' इंटरफ़ेस को लागू करता है और सफल होने पर समर्थित HTML संसाधनों में से एक का प्रतिनिधित्व करता है, या विफलता पर NULL।

### संबंधित देखें

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
