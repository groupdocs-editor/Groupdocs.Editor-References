---
title: "FontType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक समर्थित फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है"
type: docs
weight: 360
url: /hi/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

एक समर्थित फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | EOT (Embedded OpenType) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | OTF (OpenType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | TrueType Collection (TTC) फ़ॉन्ट का प्रतिनिधित्व करता है |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | TTF (TrueType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित फ़ॉन्ट संसाधन को दर्शाता है |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | WOFF (Web Open Font Format) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | WOFF2 (Web Open Font Format version 2) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | इस फ़ॉन्ट प्रकार का CSS-संगत नाम लौटाता है, जिसका उपयोग @font-face एट-रूल में किया जाता है |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | इस फ़ॉन्ट प्रकार के लिए फ़ाइलनाम एक्सटेंशन (बिंदु अक्षर के बिना) |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | @font-face फ़ॉर्मेट के लिए फ़ॉन्ट फ़ॉर्मेट |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | इस फ़ॉन्ट प्रकार का औपचारिक नाम लौटाता है |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | किसी विशेष फ़ॉन्ट प्रकार का MIME कोड |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | निर्दिष्ट सेट से पहला फ़ॉन्ट प्रकार लौटाता है, जो "Undefined" मान नहीं है, अन्यथा "Undefined" फ़ॉन्ट प्रकार लौटाता है (जब सभी आइटम "Undefined" हों) |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | फ़ॉन्ट प्रकार के निर्दिष्ट CSS-संगत नाम के समतुल्य FontType मान लौटाता है |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | निर्दिष्ट फ़ाइलनाम से निकाले गए फ़ाइलनाम एक्सटेंशन के समतुल्य FontType मान लौटाता है |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | निर्दिष्ट MIME-कोड के समतुल्य FontType मान लौटाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "FontType" इंस्टेंस के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो संभवतः एक अन्य "FontType" इंस्टेंस है |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | हैश-कोड लौटाता है, जो इस विशिष्ट मान प्रकार के लिए एक स्थिर संख्या है |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | जाँचता है कि दो "FontType" मान बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | जाँचता है कि दो "FontType" मान बराबर नहीं हैं या नहीं |

### संबंधित देखें

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
