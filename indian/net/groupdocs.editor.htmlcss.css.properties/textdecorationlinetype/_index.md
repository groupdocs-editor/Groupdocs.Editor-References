---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "टेक्स्ट डेकोरेशन लाइन के प्रकारों का प्रतिनिधित्व करता है: underline, underscore, overline और linethrough (strikethrough)।"
type: docs
weight: 290
url: /hi/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

पाठ सजावट रेखा के प्रकार को दर्शाता है: रेखांकित (अंडरस्कोर), ओवरलाइन, और स्ट्राइकथ्रू (लाइन-थ्रू)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | यह दर्शाता है कि इस इंस्टेंस का प्रारंभिक मान — None — है या नहीं। |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | यह दर्शाता है कि line-through (strikethrough) सक्षम है या नहीं। |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | यह दर्शाता है कि overline सक्षम है या नहीं। |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | यह दर्शाता है कि underline (underscore) सक्षम है या नहीं। |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | निर्दिष्ट पैरामीटरों द्वारा परिभाषित फ़्लैग्स के साथ एक [`TextDecorationLineType`](../textdecorationlinetype) इंस्टेंस बनाता और लौटाता है। |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | यह दर्शाता है कि यह [`TextDecorationLineType`](../textdecorationlinetype) उदाहरण निर्दिष्ट अनकास्टेड के बराबर है या नहीं। |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | यह दर्शाता है कि यह [`TextDecorationLineType`](../textdecorationlinetype) उदाहरण निर्दिष्ट मान के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | इस उदाहरण का हैश-कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | इस इंस्टेंस में सभी फ़्लैग्स का मान टेक्स्ट के रूप में लौटाता है। |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और एक वैध [`TextDecorationLineType`](../textdecorationlinetype) उदाहरण लौटाता है। |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | दो निर्दिष्ट लाइन प्रकारों को मिलाता (संयोजित) है और नया परिणामस्वरूप लाइन प्रकार बनाता है, जहाँ फ़्लैग्स को मिलाया जाता है (संघ)। |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | पहले और दूसरे लाइन प्रकारों के बीच प्रतिच्छेदन लौटाता है, जहाँ केवल वही फ़्लैग्स सक्षम होते हैं जो दोनों ऑपरेण्ड में एक साथ सक्षम होते हैं। सभी ऑपरेटरों में इसका सबसे उच्च प्राथमिकता है (संघ और अंतर से अधिक)। |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | जाँचता है कि दो "TextDecorationLineType" मान बराबर हैं या नहीं। |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | विशिष्ट बाइट (8-बिट ऑक्टेट) को संबंधित [`TextDecorationLineType`](../textdecorationlinetype) में कास्ट करता है, यदि कास्टिंग अमान्य है तो अपवाद फेंकता है (2 ऑपरेटर)। |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | जाँचता है कि दो "TextDecorationLineType" मान बराबर नहीं हैं या नहीं। |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | दूसरे निर्दिष्ट लाइन प्रकार को पहले निर्दिष्ट लाइन प्रकार से घटाता है और नया परिणामस्वरूप लाइन प्रकार बनाता है, जहाँ केवल पहले ऑपरेण्ड के वे फ़्लैग्स मौजूद होते हैं जो दूसरे ऑपरेण्ड में नहीं पाए जाते (अंतर)। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | पाठ की प्रत्येक पंक्ति के मध्य में एक रेखा होती है। |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | कोई टेक्स्ट सजावट नहीं बनाता। प्रारंभिक मान। |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | पाठ की प्रत्येक पंक्ति के ऊपर एक रेखा होती है। |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | पाठ की प्रत्येक पंक्ति रेखांकित होती है। |

### टिप्पणियाँ

अपरिवर्तनीय संरचना। https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line के समान।

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
