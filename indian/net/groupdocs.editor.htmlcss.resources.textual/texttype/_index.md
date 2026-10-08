---
title: "TextType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "समर्थित टेक्स्टुअल संसाधन प्रकार का प्रतिनिधित्व करता है"
type: docs
weight: 640
url: /hi/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

समर्थित टेक्स्टुअल संसाधन प्रकार का प्रतिनिधित्व करता है

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | पाठ्य संसाधन का CSS प्रकार |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित पाठ्य संसाधन को दर्शाता है |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | पाठ्य संसाधन का XML प्रकार |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | किसी विशेष पाठ्य संसाधन का फ़ाइल एक्सटेंशन (आगे के डॉट के बिना) |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | इस पाठ्य संसाधन प्रकार का औपचारिक नाम लौटाता है |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | किसी विशेष पाठ्य संसाधन प्रकार का MIME कोड |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | फ़ाइलनाम एक्सटेंशन के बराबर TextType मान लौटाता है, जो निर्दिष्ट फ़ाइलनाम से एक्सटेंशन के साथ या केवल एक्सटेंशन से निकाला जाता है |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो संभवतः एक अन्य "TextType" इंस्टेंस है |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "TextType" इंस्टेंस के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | हैश-कोड लौटाता है, जो इस विशिष्ट मान प्रकार के लिए एक स्थिर संख्या है |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | परिभाषित करता है कि दो विशिष्ट "TextType" इंस्टेंस बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | परिभाषित करता है कि दो विशिष्ट "TextType" इंस्टेंस असमान हैं या नहीं |

### संबंधित देखें

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
