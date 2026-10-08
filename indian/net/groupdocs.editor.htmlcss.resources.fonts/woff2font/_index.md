---
title: "Woff2Font"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "WOFF2 Web Open Font Format में एक फ़ॉन्ट का प्रतिनिधित्व करता है"
type: docs
weight: 400
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
## Woff2Font class

WOFF2 (Web Open Font Format) फ़ॉर्मेट में एक फ़ॉन्ट का प्रतिनिधित्व करता है।

```csharp
public sealed class Woff2Font : FontResourceBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Woff2Font](woff2font#constructor)(string, Stream) | सामग्री से, जो बाइट स्ट्रीम के रूप में प्रस्तुत है, और निर्दिष्ट नाम के साथ, नया Woff2Font क्लास बनाता है |
| [Woff2Font](woff2font#constructor_1)(string, string) | सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में प्रस्तुत है, और निर्दिष्ट नाम के साथ, नया Woff2Font क्लास बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | इस फ़ॉन्ट की सामग्री बाइट स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | इस फ़ॉन्ट रिसोर्स का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह फ़ॉन्ट नष्ट किया गया है या नहीं |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | इस फ़ॉन्ट संसाधन का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | इस फ़ॉन्ट की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है। यह मान पहली बार कॉल करने के बाद कैश किया जाता है। |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/type) { get; } | लौटाता है FontType.Woff2 |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | इस फ़ॉन्ट संसाधन को नष्ट करता है, इसकी सामग्री को नष्ट करता है और अधिकांश मेथड और प्रॉपर्टी को अकार्यशील बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | निर्दिष्ट फ़ॉन्ट संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | निर्दिष्ट HTML संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | इस फ़ॉन्ट को निर्दिष्ट फ़ाइल में सहेजता है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid)(Stream) | जाँचता है कि निर्दिष्ट स्ट्रीम एक वैध WOFF2 फ़ॉन्ट है या नहीं |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid_1)(string) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग एक वैध WOFF2 फ़ॉन्ट है या नहीं |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/requiredheadersize) | WOFF2 हेडर आकार (बाइट्स में), जो इसकी वैधता के लिए आवश्यक है |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | इवेंट, जो तब होता है जब यह फ़ॉन्ट नष्ट किया जाता है |

### संबंधित देखें

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
