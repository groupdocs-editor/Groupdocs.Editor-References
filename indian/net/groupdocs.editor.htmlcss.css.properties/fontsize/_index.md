---
title: "FontSize"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ॉन्ट आकार को एक विशेष इकाई या लंबाई मान के रूप में दर्शाता है जो फ़ॉन्ट का आकार निर्दिष्ट करता है, ऐतिहासिक रूप से बड़े अक्षर M की चौड़ाई।"
type: docs
weight: 260
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

फ़ॉन्ट आकार को एक विशेष इकाई या लंबाई मान के रूप में दर्शाता है, जो फ़ॉन्ट का आकार निर्दिष्ट करता है (ऐतिहासिक रूप से बड़े अक्षर \"M\" की चौड़ाई)।

```csharp
public struct FontSize : IEquatable<FontSize>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | यह दर्शाता है कि यह फ़ॉन्ट-साइज़ एक कीवर्ड के रूप में निरपेक्ष आकार के साथ परिभाषित है या नहीं, उपयोगकर्ता के डिफ़ॉल्ट फ़ॉन्ट आकार (जो मध्यम है) के आधार पर। |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | यह दर्शाता है कि इस फ़ॉन्ट-साइज़ का प्रारंभिक मान (Medium) है या नहीं। |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | यह दर्शाता है कि यह फ़ॉन्ट-साइज़ एक [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) मान के साथ परिभाषित है या नहीं |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | यह दर्शाता है कि यह फ़ॉन्ट-साइज़ एक कीवर्ड के रूप में सापेक्ष आकार के साथ परिभाषित है या नहीं। फ़ॉन्ट पैरेंट तत्व के फ़ॉन्ट आकार के सापेक्ष बड़ा या छोटा होगा, लगभग उसी अनुपात से जो निरपेक्ष-आकार कीवर्ड को अलग करता है। |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | एक लंबाई मान, यदि यह फ़ॉन्ट-साइज़ इसके साथ परिभाषित किया गया है, अन्यथा अपवाद फेंका जाता है |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | इस फ़ॉन्ट आकार का मान स्ट्रिंग के रूप में लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | निर्दिष्ट लंबाई से फ़ॉन्ट-साइज़ बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | निर्धारित करता है कि यह फ़ॉन्ट-साइज़ इंस्टेंस निर्दिष्ट के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | निर्धारित करता है कि यह फ़ॉन्ट-साइज़ इंस्टेंस अनकास्टेड निर्दिष्ट के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | इस इंस्टेंस के लिए हैश-कोड लौटाता है |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | निर्दिष्ट कीवर्ड को 'font-size' के उचित कीवर्ड मान के रूप में पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है। |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | जाँचता है कि दो "FontSize" मान बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | जाँचता है कि दो "FontSize" मान बराबर नहीं हैं या नहीं |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | सामान्यतः बड़ा निरपेक्ष-आकार |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | बड़ा सापेक्ष-आकार - फ़ॉन्ट पैरेंट तत्व के फ़ॉन्ट-साइज़ के सापेक्ष बड़ा होगा, लगभग उसी अनुपात से जो ऊपर निरपेक्ष-आकार कीवर्ड को अलग करता है। |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | मध्यम आकार। प्रारंभिक मान। |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | सामान्यतः छोटा निरपेक्ष-आकार |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | छोटा सापेक्ष-आकार - फ़ॉन्ट पैरेंट तत्व के फ़ॉन्ट-साइज़ के सापेक्ष छोटा होगा, लगभग उसी अनुपात से जो ऊपर निरपेक्ष-आकार कीवर्ड को अलग करता है। |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | औसत बड़ा निरपेक्ष-आकार |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | औसत छोटा निरपेक्ष-आकार |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | बहुत बड़ा निरपेक्ष-आकार |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | बहुत छोटा absolute-size |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
