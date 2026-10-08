---
title: "MetaImageBase"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "WMF और EMF इमेज फ़ॉर्मेट के लिए बेस एब्स्ट्रैक्ट क्लास"
type: docs
weight: 570
url: /hi/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

WMF और EMF इमेज फ़ॉर्मेट के लिए बेस एब्स्ट्रैक्ट क्लास

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | इस वेक्टर इमेज का आस्पेक्ट रेशियो लौटाता है। |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | इम्प्लीमेंट करने वाले प्रकार को इस वेक्टर इमेज की सामग्री को बाइट स्ट्रीम के रूप में लौटाना चाहिए। |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | इस वेक्टर इमेज का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह रास्टर इमेज नष्ट किया गया है (`true`) या नहीं (`false`). |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | इस वेक्टर इमेज के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है। |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | इस वेक्टर इमेज का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | इम्प्लीमेंट करने वाले प्रकार को इस वेक्टर इमेज की सामग्री को टेक्स्ट रूप में लौटाना चाहिए: इमेज प्रकार से संबंधित XML का base64-एन्कोडेड। |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | इम्प्लीमेंट करने वाले प्रकार को वेक्टर इमेज के प्रकार की जानकारी लौटानी चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | इम्प्लीमेंट करने वाले प्रकार को इस इंस्टेंस को नष्ट करना चाहिए। |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | निर्दिष्ट रेफ़रेंस समानता के साथ इस इंस्टेंस की जाँच करता है। |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | इम्प्लीमेंट करने वाले प्रकार को निर्दिष्ट पथ द्वारा इस इमेज को डिस्क पर सहेजना चाहिए। |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | इम्प्लीमेंट करने वाले प्रकार को वर्तमान वेक्टर इमेज को रास्टर PNG फ़ॉर्मेट में निर्दिष्ट बाइट स्ट्रीम में सहेजना चाहिए। |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | WMF या EMF प्रकार को लागू करते समय वर्तमान वेक्टर मेटा-छवि को निर्दिष्ट बाइट स्ट्रीम में वेक्टर SVG प्रारूप में सहेजना चाहिए |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | इवेंट, जो तब होता है जब यह रास्टर इमेज नष्ट किया जाता है। |

### टिप्पणियाँ

यह सारभूत वर्ग [`WmfImage`](../wmfimage) और [`EmfImage`](../emfimage) द्वारा विरासत में प्राप्त किया जाता है

### संबंधित देखें

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
