---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "मानक IDisposable इंटरफ़ेस को विस्तारित करता है, जिससे किसी ऑब्जेक्ट की वर्तमान स्थिति प्राप्त की जा सकती है और डिस्पोज़ इवेंट की सदस्यता ली जा सकती है"
type: docs
weight: 420
url: /hi/net/groupdocs.editor.htmlcss.resources/iauxdisposable/
---
## IAuxDisposable interface

मानक IDisposable इंटरफ़ेस का विस्तार करता है, किसी वस्तु की वर्तमान स्थिति प्राप्त करने और डिस्पोज़िंग इवेंट की सदस्यता लेने की अनुमति देता है

```csharp
public interface IAuxDisposable : IDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/isdisposed) { get; } | निर्धारित करता है कि संसाधन बंद है (true) या नहीं (false) |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/disposed) | ऑब्जेक्ट डिस्पोज़ होने पर होता है |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
