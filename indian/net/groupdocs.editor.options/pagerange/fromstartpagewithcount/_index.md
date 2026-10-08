---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक पेज रेंज बनाता है जो निर्दिष्ट पृष्ठ संख्या से शुरू होती है और निर्दिष्ट संख्या में पृष्ठों को शामिल करती है या अंत तक असीमित पृष्ठ गणना रखती है"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और निर्दिष्ट संख्या में पृष्ठों को शामिल करती है, या अनिश्चित पृष्ठ संख्या (अंत तक) हो सकती है।

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| startPageNumber | UInt16 | पृष्ठ संख्या, जिससे पेज रेंज समावेशी रूप से शुरू होती है। पृष्ठ संख्याएँ 1‑आधारित होती हैं, इसलिए शून्य से अधिक होना आवश्यक है |
| pageCount | UInt16 | पृष्ठों की संख्या, शून्य से अधिक होनी चाहिए। यदि शून्य हो - इसका अर्थ है दस्तावेज़ के अंत तक सभी पृष्ठ |

### रिटर्न मान

नया PageRange इंस्टेंस

### संबंधित देखें

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
