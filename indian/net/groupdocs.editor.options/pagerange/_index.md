---
title: "PageRange"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक पेज रेंज को संलग्न करता है जिसमें खुले या बंद सीमाएँ हो सकती हैं। डिफ़ॉल्ट रूप से यह पूरी तरह खुला होता है और सभी मौजूदा पृष्ठों को शामिल करता है। पेज क्रमांक 1 से शुरू होता है, 0 से नहीं।"
type: docs
weight: 1030
url: /hi/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

एक पृष्ठ रेंज को समाहित करता है, जिसमें खुली या बंद सीमाएँ हो सकती हैं। डिफ़ॉल्ट रूप से "पूर्णतः खुला" होता है - यह सभी मौजूदा पृष्ठों को शामिल करता है। पृष्ठ क्रमांक 1 से शुरू होता है, 0 से नहीं।

```csharp
public struct PageRange : IEquatable<PageRange>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | रेंज के भीतर पृष्ठों की संख्या। यदि 0 - पेज रेंज दस्तावेज़ के अंत तक फैलती है चाहे उसमें कितने भी पृष्ठ हों। |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | विशिष्ट समाप्ति पेज संख्या, जिसके तक यह पेज रेंज जारी रहती है और जिस पर यह विशेष रूप से समाप्त होती है। यदि 0 - पेज रेंज दस्तावेज़ के अंत तक फैलती है। |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | निर्दिष्ट करता है कि यह इंस्टेंस डिफ़ॉल्ट \"पूरी तरह खुला\" पेज रेंज दर्शाता है यानी यह दस्तावेज़ के सभी पृष्ठों को दर्शाता है (true) या नहीं (false)। |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | समावेशी प्रारंभ पेज संख्या, जिससे यह पेज रेंज शुरू होती है। यदि 1 - पेज रेंज दस्तावेज़ के पहले पेज से शुरू होती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | एक पेज रेंज बनाता है, जो पहले पेज से शुरू होती है और निर्दिष्ट संख्या में पृष्ठों को शामिल करती है। |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और दस्तावेज़ के अंत तक जारी रहती है। |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या (समावेशी) से शुरू होती है और निर्दिष्ट पेज संख्या (विशिष्ट) तक जारी रहती है। |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और निर्दिष्ट संख्या में पृष्ठों को शामिल करती है, या अनिश्चित पृष्ठ संख्या (अंत तक) हो सकती है। |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | पता लगाता है कि यह PageRange इंस्टेंस निर्दिष्ट के बराबर है या नहीं। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | दस्तावेज़ के सभी मौजूदा पृष्ठों का प्रतिनिधित्व करता है। डिफ़ॉल्ट मान। |

### टिप्पणियाँ

एक अपरिवर्तनीय स्ट्रक्ट, जो पृष्ठ रेंज को समाहित करता है, जो किसी विशिष्ट दस्तावेज़ से संबंधित नहीं है, और किसी भी दस्तावेज़ के लिए पृष्ठ रेंज का प्रतिनिधित्व कर सकता है।

### संबंधित देखें

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
