---
title: "OtfFont"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "दिए गए नाम के साथ base64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री से नया OtfFont क्लास बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाई गई है, नया OtfFont क्लास बनाता है, और निर्दिष्ट नाम के साथ

```csharp
public OtfFont(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | OTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| contentInBase64 | String | सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह OTF सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, नया OtfFont क्लास बनाता है, और निर्दिष्ट नाम के साथ

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | OTF फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
