---
title: "अनुपात"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक अनुपात CSS डेटा प्रकार का प्रतिनिधित्व करता है जिसका उपयोग मीडिया क्वेरीज़ में एस्पेक्ट अनुपात और रास्टर छवियों को वर्णित करने के लिए किया जाता है, जहाँ दो बिना इकाई वाले मानों को अंश (numerator) और हर (denominator) कहा जाता है। अपरिवर्तनीय संरचना।"
type: docs
weight: 250
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

एक "ratio" CSS डेटा प्रकार का प्रतिनिधित्व करता है, जिसका उपयोग मीडिया क्वेरी में अनुपात वर्णन करने और रास्टर छवियों में दो बिना इकाई वाले मानों "numerator" और "denominator" के बीच अनुपात दर्शाने के लिए किया जाता है। अपरिवर्तनीय संरचना।

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | इस अनुपात का हर लौटाता है |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | निर्धारित करता है कि यह अनुपात डिफ़ॉल्ट मान रखता है या "1/1" (एकल) है |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | इस अनुपात का अंश लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | निर्दिष्ट अंश और हर से एक Ratio इंस्टेंस बनाता और लौटाता है |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | इस अनुपात की गणना करता है और इसे एकल फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | इस अनुपात की पूरी कॉपी लौटाता है |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो संभवतः एक अन्य "Ratio" इंस्टेंस है |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "Ratio" इंस्टेंस के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे उसके जीवनकाल के दौरान बदला नहीं जा सकता |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | इस अनुपात के लिए एक उलटा (प्रतिलोम) अनुपात बनाता और लौटाता है |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | इस अनुपात को स्ट्रिंग में क्रमबद्ध करता है और उसे लौटाता है |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | इस अनुपात का स्ट्रिंग प्रतिनिधित्व लौटाता है; यह "SerializeDefault()" के समान है |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | दोनों अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं या नहीं। |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | दो अनुपातों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते हैं। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | एकल डिफ़ॉल्ट अनुपात 1/1 |

### टिप्पणियाँ

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### संबंधित देखें

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
