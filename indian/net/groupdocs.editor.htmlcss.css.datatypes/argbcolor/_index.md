---
title: "ArgbColor"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "32 बिट ARGB फ़ॉर्मेट में 8 बिट प्रति चैनल सहित पारदर्शिता के साथ एक रंग मान का प्रतिनिधित्व करता है, जिसमें कनवर्टर और सीरियलाइज़र शामिल हैं।"
type: docs
weight: 160
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

32-बिट ARGB प्रारूप (पारदर्शिता सहित प्रत्येक चैनल के 8 बिट) में एक रंग मान का प्रतिनिधित्व करता है, जिसमें परिवर्तक और सीरियलाइज़र शामिल हैं

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | रंग के अल्फा भाग को प्राप्त करता है। |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | रंग के अल्फा भाग को प्रतिशत में प्राप्त करता है (0..1)। |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | रंग के नीले भाग को प्राप्त करता है। |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | रंग के हरे भाग को प्राप्त करता है। |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | यह संकेत देता है कि यह [`ArgbColor`](../argbcolor) उदाहरण डिफ़ॉल्ट (पारदर्शी) है - सभी 4 चैनल 0 पर सेट हैं। |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | अप्रारंभित रंग - सभी 4 चैनल 0 पर सेट हैं। डिफ़ॉल्ट और पारदर्शी के समान। |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | यह संकेत देता है कि यह [`ArgbColor`](../argbcolor) उदाहरण पूरी तरह अपारदर्शी है, बिना पारदर्शिता के (इसका अल्फा चैनल अधिकतम मान रखता है)। |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | यह संकेत देता है कि यह [`ArgbColor`](../argbcolor) उदाहरण पूरी तरह पारदर्शी है - इसका अल्फा चैनल न्यूनतम (0) मान रखता है, इसलिए अन्य R, G, और B चैनलों का कोई दृश्यमान प्रभाव नहीं रहता। |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | यह संकेत देता है कि यह [`ArgbColor`](../argbcolor) उदाहरण अर्धपारदर्शी है (पूरी तरह पारदर्शी नहीं, लेकिन पूरी तरह अपारदर्शी भी नहीं)। |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | रंग के लाल भाग को प्राप्त करता है। |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | रंग का Int32 मान प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | निर्दिष्ट लाल, हरा, नीला चैनलों से एक [`ArgbColor`](../argbcolor) मान बनाता है, जबकि अल्फा चैनल पूरी तरह अपारदर्शी होता है |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | निर्दिष्ट लाल, हरा, नीला और अल्फा चैनलों से एक [`ArgbColor`](../argbcolor) मान बनाता है |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | एकल मान से पूरी तरह अपारदर्शी (A=255) रंग बनाता है, जो सभी चैनलों पर लागू होगा |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | दो [`ArgbColor`](../argbcolor) रंगों की समानता जाँचता है |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | जाँचता है कि कोई अन्य वस्तु इस [`ArgbColor`](../argbcolor) उदाहरण के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | वर्तमान रंग को परिभाषित करने वाला हैश कोड लौटाता है। |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | पारदर्शिता के आधार पर इस [`ArgbColor`](../argbcolor) उदाहरण को सबसे उपयुक्त CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | इस [`ArgbColor`](../argbcolor) उदाहरण को 'rgb' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | इस [`ArgbColor`](../argbcolor) उदाहरण को 'rgba' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | के समान [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं या नहीं। |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | दो रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | सभी "ज्ञात रंगों", जो CSS मानक में स्थिर अद्वितीय नाम और मान रखते हैं, को शामिल करता है |

### टिप्पणियाँ

यह प्रकार (परंतु केवल CSS संचालन तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### संबंधित देखें

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
