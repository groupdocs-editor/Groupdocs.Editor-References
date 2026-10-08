---
title: "SvgImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सामान्य स्ट्रिंग के रूप में प्रस्तुत सामग्री और निर्दिष्ट नाम से नया SvgImage इंस्टेंस बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

सामग्री से, जो सामान्य स्ट्रिंग के रूप में दर्शाई गई है, नया SvgImage इंस्टेंस बनाता है, और निर्दिष्ट नाम के साथ

```csharp
public SvgImage(string name, string content)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | SVG छवि का नाम। यह null, खाली या whitespace नहीं हो सकता। |
| सामग्री | String | सामग्री एक सामान्य स्ट्रिंग के रूप में, जिसमें SVG छवि की वैध XML‑अनुपालक सामग्री होती है। यह null, खाली या whitespace नहीं हो सकता। यदि यह SVG सामग्री नहीं है, तो अपवाद उत्पन्न होगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | कुछ पैरामीटर अमान्य हैं |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* तर्क में अमान्य SVG सामग्री है |

### संबंधित देखें

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, नया SvgImage इंस्टेंस बनाता है, और निर्दिष्ट नाम के साथ

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | SVG छवि का नाम। यह null, खाली या whitespace नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
