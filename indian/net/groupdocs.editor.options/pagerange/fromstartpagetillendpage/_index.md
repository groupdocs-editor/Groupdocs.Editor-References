---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक पेज रेंज बनाता है जो निर्दिष्ट पृष्ठ संख्या से समावेशी रूप से शुरू होती है और निर्दिष्ट पृष्ठ संख्या तक विशेष रूप से जारी रहती है"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या (समावेशी) से शुरू होती है और निर्दिष्ट पेज संख्या (विशिष्ट) तक जारी रहती है।

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| startPageNumber | UInt16 | पृष्ठ संख्या, जिससे पेज रेंज समावेशी रूप से शुरू होती है। पृष्ठ संख्याएँ 1‑आधारित होती हैं, इसलिए शून्य से अधिक होना आवश्यक है |
| endPageNumber | UInt16 | पृष्ठ संख्या, जिसके तक पेज रेंज विशेष रूप से जारी रहती है। पृष्ठ संख्याएँ 1‑आधारित होती हैं, इसलिए शून्य से अधिक होना आवश्यक है, और साथ ही *startPageNumber* से भी अधिक होना चाहिए |

### संबंधित देखें

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
