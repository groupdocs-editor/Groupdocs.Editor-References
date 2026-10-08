---
title: "EotFont"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "नए EotFont क्लास को base64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री और निर्दिष्ट नाम से बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में प्रदर्शित है, और निर्दिष्ट नाम के साथ, नया EotFont क्लास बनाता है

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| eotName | String | EOT फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| eotContentInBase64 | String | सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह EOT सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में प्रदर्शित है, और निर्दिष्ट नाम के साथ, नया EotFont क्लास बनाता है

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| eotName | String | EOT फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| eotBinaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
