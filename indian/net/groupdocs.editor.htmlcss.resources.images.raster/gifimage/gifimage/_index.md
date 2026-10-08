---
title: "GifImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "base64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री और निर्दिष्ट नाम से नया GifImage इंस्टेंस बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/gifimage/
---
## GifImage(string, string) {#constructor_1}

सामग्री से नया GifImage इंस्टेंस बनाता है, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाया गया है, और निर्दिष्ट नाम के साथ

```csharp
public GifImage(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | GIF छवि का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
| contentInBase64 | String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या व्हाइटस्पेस नहीं हो सकता। यदि यह GIF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## GifImage(string, Stream) {#constructor}

सामग्री से नया GifImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, और निर्दिष्ट नाम के साथ

```csharp
public GifImage(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | GIF छवि का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
