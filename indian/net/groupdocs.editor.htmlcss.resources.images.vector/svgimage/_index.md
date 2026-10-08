---
title: "SvgImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "SVG स्केलेबल वेक्टर ग्राफिक्स फ़ॉर्मेट में एक वेक्टर छवि का प्रतिनिधित्व करता है, जिसमें उसके मेटाडेटा आयाम और PNG में सहेजने के अतिरिक्त मेथड्स होते हैं"
type: docs
weight: 580
url: /hi/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

SVG (Scalable Vector Graphics) फ़ॉर्मेट में एक वेक्टर इमेज का प्रतिनिधित्व करता है, साथ में उसका मेटाडेटा (आकार) और अतिरिक्त मेथड्स (PNG में सहेजना)।

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | सामग्री से, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, नया SvgImage इंस्टेंस बनाता है, और निर्दिष्ट नाम के साथ |
| [SvgImage](svgimage#constructor_1)(string, string) | सामग्री से, जो सामान्य स्ट्रिंग के रूप में दर्शाई गई है, नया SvgImage इंस्टेंस बनाता है, और निर्दिष्ट नाम के साथ |

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | इस वेक्टर इमेज का आस्पेक्ट रेशियो लौटाता है। |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | इस SVG छवि की सामग्री को मूल स्थिति के साथ बाइनरी स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | इस वेक्टर इमेज का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह रास्टर इमेज नष्ट किया गया है (`true`) या नहीं (`false`). |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | इस वेक्टर इमेज के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है। |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | इस वेक्टर इमेज का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | इस SVG छवि की सामग्री को base64-एन्कोडेड बाइनरी कंटेंट के रूप में लौटाता है (XML फ़ॉर्मेट में कच्चे टेक्स्ट के रूप में नहीं) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | लौटाता है [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | इस SVG छवि की सामग्री को उसके मूल XML-अनुपालन टेक्स्ट फ़ॉर्म में लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | निर्दिष्ट रेफ़रेंस समानता के साथ इस इंस्टेंस की जाँच करता है। |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | इस SVG छवि को फ़ाइल में सहेजता है |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | इस वेक्टर SVG छवि को रास्टर PNG छवि में सहेजता है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | जाँचता है कि निर्दिष्ट टेक्स्टुअल XML-अनुपालन सामग्री SVG छवि का प्रतिनिधित्व करती है या नहीं |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | इवेंट, जो तब होता है जब यह रास्टर इमेज नष्ट किया जाता है। |

### संबंधित देखें

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
