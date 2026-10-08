---
title: "FontStyle"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "परिभाषित करता है कि फ़ॉन्ट को उसके फ़ॉन्टफ़ैमिली से सामान्य, इटैलिक या ऑब्लिक फ़ेस के साथ कैसे स्टाइल किया जाना चाहिए।"
type: docs
weight: 270
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

परिभाषित करता है कि फ़ॉन्ट को उसके फ़ॉन्ट-फ़ैमिली से सामान्य, इटैलिक या ऑब्लीक फेस के साथ कैसे स्टाइल किया जाना चाहिए।

```csharp
public struct FontStyle
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | बताता है कि इस फ़ॉन्ट-स्टाइल का प्रारंभिक मान (Normal) है या नहीं |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | इस फ़ॉन्ट स्टाइल का मान स्ट्रिंग के रूप में लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | निर्धारित करता है कि यह फ़ॉन्ट-स्टाइल इंस्टेंस निर्दिष्ट के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | निर्धारित करता है कि यह फ़ॉन्ट-स्टाइल इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | इस इंस्टेंस के लिए हैश-कोड लौटाता है |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | निर्दिष्ट कीवर्ड को 'font-style' का उचित कीवर्ड वैल्यू मानने की कोशिश करता है और सफलता पर उसे लौटाता है या विफलता पर NULL लौटाता है। |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | जाँचता है कि दो "FontStyle" मान बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | जाँचता है कि दो "FontStyle" मान बराबर नहीं हैं या नहीं |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | इटैलिक के रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। यदि फ़ेस का कोई इटैलिक संस्करण उपलब्ध नहीं है, तो इसके बजाय ओब्लिक के रूप में वर्गीकृत फ़ॉन्ट उपयोग किया जाता है। यदि दोनों उपलब्ध नहीं हैं, तो शैली को कृत्रिम रूप से सिम्युलेट किया जाता है। |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | फ़ॉन्ट-फ़ैमिली के भीतर सामान्य के रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। प्रारंभिक मान। |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | ओब्लिक के रूप में वर्गीकृत फ़ॉन्ट का चयन करता है। यदि फ़ेस का कोई ओब्लिक संस्करण उपलब्ध नहीं है, तो इसके बजाय इटैलिक के रूप में वर्गीकृत फ़ॉन्ट उपयोग किया जाता है। यदि दोनों उपलब्ध नहीं हैं, तो शैली को कृत्रिम रूप से सिम्युलेट किया जाता है। |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
