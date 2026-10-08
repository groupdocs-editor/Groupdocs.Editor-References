---
title: "TtfFont"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "नए TtfFont क्लास को base64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री और निर्दिष्ट नाम से बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में प्रदर्शित है, और निर्दिष्ट नाम के साथ, नया TtfFont क्लास बनाता है

```csharp
public TtfFont(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | TTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| contentInBase64 | String | सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह TTF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में प्रदर्शित है, और निर्दिष्ट नाम के साथ, नया TtfFont क्लास बनाता है

```csharp
public TtfFont(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | TTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | जब निर्दिष्ट बाइनरी सामग्री को सही ढंग से वैध TTF फ़ॉन्ट के रूप में व्याख्या नहीं किया जा सकता, तब फेंका जाता है |

### संबंधित देखें

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
