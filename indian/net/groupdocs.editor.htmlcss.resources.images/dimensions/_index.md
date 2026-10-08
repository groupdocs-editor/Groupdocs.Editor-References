---
title: "आयाम"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक रास्टर आयताकार छवि की रैखिक आयाम (चौड़ाई और ऊँचाई) को मनमाने इकाई में दर्शाता है। अपरिवर्तनीय स्ट्रक्ट।"
type: docs
weight: 450
url: /hi/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

एक रास्टर आयताकार छवि के रैखिक आयाम (चौड़ाई और ऊँचाई) को मनमाने इकाई में दर्शाता है। अपरिवर्तनीय स्ट्रक्ट।

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | निर्दिष्ट चौड़ाई और ऊँचाई से एक नया इंस्टेंस बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | एक खाली Dimensions इंस्टेंस लौटाता है |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | क्षेत्रफल (चौड़ाई x ऊँचाई) लौटाता है |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | इन आयामों का अनुपात चौड़ाई/ऊँचाई के रूप में |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | छवि की ऊँचाई लौटाता है। |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | निर्धारित करता है कि यह "Dimensions" इंस्टेंस खाली और डिफ़ॉल्ट है या नहीं, अर्थात यह सही चौड़ाई और ऊँचाई संग्रहीत नहीं करता। |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | निर्धारित करता है कि निर्दिष्ट 'Dimensions' वर्ग वर्ग (square) दर्शाता है या नहीं, अर्थात यदि चौड़ाई ऊँचाई के बराबर है। |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | छवि की चौड़ाई लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | इस इंस्टेंस की पूरी कॉपी लौटाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "Dimensions" इंस्टेंस के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो संभवतः एक अन्य "Dimensions" इंस्टेंस है |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे उसके जीवनकाल के दौरान बदला नहीं जा सकता |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो वर्तमान से अनुपातिक रूप से निर्दिष्ट ऊँचाई के आधार पर आकार बदलता है |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो वर्तमान से अनुपातिक रूप से निर्दिष्ट चौड़ाई के आधार पर आकार बदलता है |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | इस "Dimensions" की स्ट्रिंग प्रतिनिधित्व लौटाता है |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | जाँचता है कि दो "Dimensions" मान बराबर हैं या नहीं, अर्थात उनकी चौड़ाई और ऊँचाई समान हैं, या दोनों खाली हैं |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | जाँचता है कि दो "Dimensions" मान असमान हैं या नहीं, अर्थात उनकी संबंधित चौड़ाई और/या ऊँचाई अलग हैं |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
