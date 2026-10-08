---
title: "IconImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट नाम के साथ बेस64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री से नया IconImage इंस्टेंस बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/iconimage/
---
## IconImage(string, string) {#constructor_1}

निर्दिष्ट नाम के साथ, बेस64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री से नया IconImage इंस्टेंस बनाता है

```csharp
public IconImage(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | ICON छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
| contentInBase64 | String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। यह null, खाली या whitespace नहीं हो सकता। यदि यह ICON सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IconImage(string, Stream) {#constructor}

निर्दिष्ट नाम के साथ, बाइट स्ट्रीम के रूप में प्रस्तुत सामग्री से नया IconImage इंस्टेंस बनाता है

```csharp
public IconImage(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | ICON छवि का नाम। null, खाली या whitespace नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
