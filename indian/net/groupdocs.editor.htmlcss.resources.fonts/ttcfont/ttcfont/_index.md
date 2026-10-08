---
title: "TtcFont"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट नाम के साथ और base64-एन्कोडेड स्ट्रिंग के रूप में प्रतिनिधित्व वाली सामग्री से नया TtcFont क्लास बनाता है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया TtcFont क्लास बनाता है

```csharp
public TtcFont(string name, string contentInBase64)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | TTC फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| contentInBase64 | String | सामग्री base64-एन्कोडेड स्ट्रिंग के रूप में। null, खाली या whitespace नहीं हो सकता। यदि यह TTC सामग्री नहीं है, तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | इनपुट स्ट्रिंग में से कोई भी `null`, खाली या केवल whitespace है |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *contentInBase64* तर्क में सामग्री को वैध TTC फ़ॉन्ट के रूप में पहचान नहीं सकता |

### संबंधित देखें

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया TtcFont क्लास बनाता है

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| name | String | TTC फ़ॉन्ट का नाम। null, खाली या whitespace नहीं हो सकता। |
| binaryContent | Stream | सामग्री को बाइट स्ट्रीम के रूप में। पढ़ना मूल स्थिति से शुरू होता है। null नहीं हो सकता। पढ़ने योग्य और सीकएबल होना चाहिए। यदि यह इंस्टेंस डिस्पोज़ किया जाएगा, तो यह स्ट्रीम भी डिस्पोज़ हो जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | *name* तर्क `null`, खाली या केवल whitespace है |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | जब निर्दिष्ट बाइनरी सामग्री को सही ढंग से वैध TTF फ़ॉन्ट के रूप में व्याख्या नहीं किया जा सकता, तब फेंका जाता है |

### संबंधित देखें

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
