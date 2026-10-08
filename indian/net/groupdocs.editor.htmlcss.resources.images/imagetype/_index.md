---
title: "ImageType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक समर्थित इमेज प्रकार फ़ॉर्मेट का प्रतिनिधित्व करता है जो रास्टर और वेक्टर दोनों फ़ॉर्मेट को समर्थन देता है।"
type: docs
weight: 480
url: /hi/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

एक समर्थित छवि प्रकार (फ़ॉर्मेट) का प्रतिनिधित्व करता है, जो रास्टर और वेक्टर दोनों फ़ॉर्मेट को समर्थन देता है।

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | BMP इमेज प्रकार |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF (Enhanced MetaFile) वेक्टर इमेज प्रकार |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | GIF इमेज प्रकार |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | ICON इमेज प्रकार |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | JPEG इमेज प्रकार |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | PNG इमेज प्रकार |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | SVG वेक्टर छवि प्रकार |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF (Tagged Image File Format) रास्टर छवि प्रकार |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | अपरिभाषित छवि प्रकार - विशेष मान, जो सामान्यतः नहीं होना चाहिए |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF (Windows MetaFile) वेक्टर छवि प्रकार |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | किसी विशिष्ट छवि प्रकार का फ़ाइल एक्सटेंशन (शुरुआती बिंदु के बिना) छोटे अक्षरों में। अपरिभाषित प्रकार के लिए स्ट्रिंग 'unsefined' लौटाता है। |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | इस छवि फ़ॉर्मेट का औपचारिक नाम लौटाता है। कभी NULL नहीं लौटाता। यदि इंस्टेंस भ्रष्ट नहीं है, तो कभी अपवाद नहीं फेंकता। |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | यह दर्शाता है कि यह विशेष फ़ॉर्मेट वेक्टर (true) है या रास्टर (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | किसी विशिष्ट छवि प्रकार का MIME कोड स्ट्रिंग के रूप में। अपरिभाषित प्रकार के लिए स्ट्रिंग 'unsefined' लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | ImageType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के बराबर है, जो निर्दिष्ट फ़ाइलनाम से निकाला गया है |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | ImageType मान लौटाता है, जो निर्दिष्ट MIME कोड के बराबर है |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "ImageType" इंस्टेंस के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो संभवतः एक अन्य "ImageType" इंस्टेंस है |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | हैश-कोड लौटाता है, जो इस विशिष्ट इंस्टेंस के लिए अपरिवर्तनीय संख्या है |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | FormalName प्रॉपर्टी लौटाता है |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | परिभाषित करता है कि दो विशिष्ट ImageType इंस्टेंस असमान हैं या नहीं |

### संबंधित देखें

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
