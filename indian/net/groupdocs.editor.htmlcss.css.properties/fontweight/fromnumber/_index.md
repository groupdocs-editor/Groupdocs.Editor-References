---
title: "FromNumber"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट संख्या से एक फ़ॉन्टवेट बनाता है"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

निर्दिष्ट संख्या से एक font-weight बनाता है।

```csharp
public static FontWeight FromNumber(ushort number)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| संख्या | UInt16 | अहस्ताक्षरित पूर्णांक, [1..1000] सीमा के भीतर होना चाहिए |

### रिटर्न मान

नया FontWeight इंस्टेंस या अपवाद

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट संख्या [1..1000] सीमा से बाहर है |

### संबंधित देखें

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
