---
title: "WmfImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट नाम के साथ बेस64 एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत सामग्री से नया WmfImage इंस्टेंस बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया WmfImage इंस्टेंस बनाता है

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | WMF इमेज का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
| contentInBase64 | String | सामग्री को बेस64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या व्हाइटस्पेस नहीं हो सकता। यदि यह WMF सामग्री नहीं है, तो एक्सेप्शन फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया WmfImage इंस्टेंस बनाता है

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | WMF इमेज का नाम। null, खाली या व्हाइटस्पेस नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### संबंधित देखें

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
