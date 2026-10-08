---
title: "WmfImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "WMF Windows MetaFile प्रारूप में एक वेक्टर छवि का प्रतिनिधित्व करता है, जिसमें उसका मेटाडाटा और अतिरिक्त विधियाँ शामिल हैं"
type: docs
weight: 600
url: /hi/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

WMF (Windows MetaFile) फ़ॉर्मेट में एक वेक्टर इमेज का प्रतिनिधित्व करता है, साथ में उसका मेटाडेटा और अतिरिक्त मेथड्स।

```csharp
public sealed class WmfImage : MetaImageBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया WmfImage इंस्टेंस बनाता है |
| [WmfImage](wmfimage#constructor_1)(string, string) | सामग्री से, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाई गई है, और निर्दिष्ट नाम के साथ नया WmfImage इंस्टेंस बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | इस वेक्टर इमेज का आस्पेक्ट रेशियो लौटाता है। |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | इस WMF छवि की सामग्री को बाइनरी स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | इस वेक्टर इमेज का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह रास्टर इमेज नष्ट किया गया है (`true`) या नहीं (`false`). |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | इस वेक्टर इमेज के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है। |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | इस वेक्टर इमेज का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | इस WMF छवि की सामग्री को साधारण टेक्स्ट के रूप में लौटाता है |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | ImageType.Wmf लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | इस WMF छवि को उसकी सामग्री को नष्ट करके और उसकी अधिकांश विधियों और गुणों को निष्क्रिय करके नष्ट करता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | निर्दिष्ट रेफ़रेंस समानता के साथ इस इंस्टेंस की जाँच करता है। |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | इस WMF छवि को फ़ाइल में सहेजता है |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | इस वेक्टर WMF छवि को रास्टर PNG छवि में सहेजता है |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | इस वेक्टर WMF छवि को वेक्टर SVG छवि में सहेजता है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध WMF छवि है या नहीं |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध WMF छवि है या नहीं |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | इवेंट, जो तब होता है जब यह रास्टर इमेज नष्ट किया जाता है। |

### संबंधित देखें

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
