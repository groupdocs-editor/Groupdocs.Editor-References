---
title: "FontResourceBase"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "HTML दस्तावेज़ के लिए सभी गुणों के साथ एक रिसोर्स के रूप में किसी भी समर्थित फ़ॉन्ट प्रकार के लिए बेस क्लास।"
type: docs
weight: 350
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

HTML दस्तावेज़ के लिए सभी गुणों के साथ एक रिसोर्स के रूप में किसी भी समर्थित फ़ॉन्ट प्रकार के लिए बेस क्लास।

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | इस फ़ॉन्ट की सामग्री बाइट स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | इस फ़ॉन्ट रिसोर्स का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह फ़ॉन्ट नष्ट किया गया है या नहीं |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | इस फ़ॉन्ट संसाधन का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | इस फ़ॉन्ट की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है। यह मान पहली बार कॉल करने के बाद कैश किया जाता है। |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | इम्प्लीमेंटिंग टाइप को विशिष्ट फ़ॉन्ट रिसोर्स के प्रकार की जानकारी एक विशिष्ट FontType टाइप की इंस्टेंस के रूप में लौटानी चाहिए, जो सभी टाइप-विशिष्ट जानकारी को समाहित करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | इस फ़ॉन्ट संसाधन को नष्ट करता है, इसकी सामग्री को नष्ट करता है और अधिकांश मेथड और प्रॉपर्टी को अकार्यशील बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | निर्दिष्ट फ़ॉन्ट संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | निर्दिष्ट HTML संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | इस फ़ॉन्ट को निर्दिष्ट फ़ाइल में सहेजता है |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | इवेंट, जो तब होता है जब यह फ़ॉन्ट नष्ट किया जाता है |

### संबंधित देखें

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
