---
title: "IHtmlResource"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "अज्ञात HTML संसाधन रास्टर या वेक्टर इमेज, स्टाइलशीट, फ़ॉन्ट, टेक्स्ट रिसोर्स, CSS, XML, ऑडियो आदि का एक उदाहरण दर्शाता है।"
type: docs
weight: 430
url: /hi/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

अज्ञात HTML संसाधन (रास्टर या वेक्टर इमेज, स्टाइलशीट, फ़ॉन्ट, टेक्स्ट संसाधन (CSS, XML), ऑडियो आदि) का एक उदाहरण दर्शाता है

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | HTML संसाधन की सामग्री बाइट स्ट्रीम के रूप में |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | निर्दिष्ट संसाधन का सही फ़ाइलनाम उपयुक्त फ़ाइल एक्सटेंशन के साथ |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | HTML संसाधन का नाम |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | बाइनरी संसाधनों के लिए बेस64-एन्कोडेड टेक्स्ट स्ट्रिंग या टेक्स्टुअल संसाधनों के लिए साधारण टेक्स्ट के रूप में HTML संसाधन की सामग्री |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | HTML संसाधन का प्रकार |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | वर्तमान संसाधन को निर्दिष्ट फ़ाइल में सहेजता है |

### संबंधित देखें

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
