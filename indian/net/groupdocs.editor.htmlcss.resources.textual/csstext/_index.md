---
title: "CssText"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक CSS टेक्स्टुअल संसाधन का प्रतिनिधित्व करता है"
type: docs
weight: 620
url: /hi/net/groupdocs.editor.htmlcss.resources.textual/csstext/
---
## CssText class

एक CSS टेक्स्टुअल संसाधन का प्रतिनिधित्व करता है

```csharp
public sealed class CssText : TextResourceBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | इस टेक्स्ट रिसोर्स की सामग्री को मूल एन्कोडिंग के साथ बाइट स्ट्रीम के रूप में लौटाता है |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | इस टेक्स्टुअल रिसोर्स की एन्कोडिंग लौटाता है। आमतौर पर UTF-8 लौटाता है। |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | इस टेक्स्ट रिसोर्स का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह टेक्स्ट रिसोर्स डिस्पोज़ किया गया है या नहीं |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | फ़ाइल एक्सटेंशन के बिना इस टेक्स्ट रिसोर्स का नाम लौटाता है |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | इस टेक्स्ट रिसोर्स की सामग्री को एक मानक स्ट्रिंग के रूप में लौटाता है |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/csstext/type) { get; } | TextType.Css लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | इस टेक्स्ट रिसोर्स को डिस्पोज़ करता है, इसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है। कई कॉल्स को सहनशील। |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | इस इंस्टेंस को निर्दिष्ट के साथ समानता पर जांचता है। |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | इस टेक्स्ट रिसोर्स को निर्दिष्ट फ़ाइल में सहेजता है |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | इवेंट, जो तब होता है जब यह टेक्स्ट रिसोर्स डिस्पोज़ किया जाता है |

### संबंधित देखें

* class [TextResourceBase](../textresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
