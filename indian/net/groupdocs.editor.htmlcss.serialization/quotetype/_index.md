---
title: "QuoteType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "उद्धरण अक्षरों को दर्शाता है: सिंगल कोट और डबल कोट"
type: docs
weight: 660
url: /hi/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

उद्धरण वर्णों का प्रतिनिधित्व करता है - सिंगल कोट (') और डबल कोट (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | उद्धरण के लिए अक्षर |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | वर्तमान अक्षर का कोड पॉइंट (U+0027 या U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | HTML-एन्कोडेड अक्षर |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | यह दर्शाता है कि इस उद्धरण प्रकार की इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | यह दर्शाता है कि इस उद्धरण प्रकार की इंस्टेंस निर्दिष्ट के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | इस अक्षर के लिए हैश-कोड लौटाता है |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | वर्तमान मान के आधार पर "SingleQuote" या "DoubleQuote" स्ट्रिंग लौटाता है |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | जाँचता है कि दो "QuoteType" मान बराबर हैं या नहीं |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | निर्दिष्ट [`QuoteType`](../quotetype) इंस्टेंस को Char में कास्ट करता है (2 ऑपरेटर) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | जाँचता है कि दो "QuoteType" मान बराबर नहीं हैं |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | डबल कोट (U+0022 QUOTATION MARK अक्षर) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | सिंगल कोट (U+0027 APOSTROPHE अक्षर) |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
