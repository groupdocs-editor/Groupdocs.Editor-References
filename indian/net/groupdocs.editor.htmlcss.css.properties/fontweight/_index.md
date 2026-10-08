---
title: "FontWeight"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Fontweight प्रॉपर्टी फ़ॉन्ट के वजन या बोल्डनेस को सेट करती है। उपलब्ध वजन वर्तमान में सेट किए गए fontfamily पर निर्भर करते हैं।"
type: docs
weight: 280
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

फ़ॉन्ट-वेट प्रॉपर्टी फ़ॉन्ट का वजन (या बोल्डनेस) सेट करती है। उपलब्ध वेट्स वर्तमान में सेट किए गए फ़ॉन्ट-फ़ैमिली पर निर्भर करते हैं।

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | यह दर्शाता है कि यह font-weight इंस्टेंस फ़ॉन्ट के वजन (बोल्डनेस) का पूर्णांक मान के रूप में एक absolute मान संग्रहीत करता है या नहीं। |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | यह दर्शाता है कि इस फ़ॉन्ट-साइज़ का प्रारंभिक मान (Medium) है या नहीं। |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | यह दर्शाता है कि यह font-weight इंस्टेंस फ़ॉन्ट के वजन (बोल्डनेस) का सापेक्ष मान संग्रहीत करता है - पैरेंट एलिमेंट की बोल्डनेस की तुलना में। |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | एक संख्या लौटाता है - 1 से 1000 के बीच का पूर्णांक मान, जिसमें फ़ॉन्ट की बोल्डनेस का वर्णन होता है, या यदि वर्तमान बोल्डनेस absolute नहीं बल्कि relative है तो एक अपवाद फेंकता है। |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | इस font-weight का मान स्ट्रिंग के रूप में लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | निर्दिष्ट संख्या से एक font-weight बनाता है। |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | निर्दिष्ट FontWeight इंस्टेंस समान हैं या नहीं निर्धारित करता है। |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | यह निर्धारित करता है कि यह FontWeight इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | इस इंस्टेंस के लिए हैश-कोड लौटाता है |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | निर्दिष्ट स्ट्रिंग को पार्स करने का प्रयास करता है और सफल होने पर एक वैध FontWeight इंस्टेंस लौटाता है। |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | जाँचता है कि दो \"FontWeight\" मान समान हैं या नहीं। |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | जाँचता है कि दो \"FontWeight\" मान असमान हैं या नहीं। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | बोल्ड फ़ॉन्ट वजन। 700 के समान। |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | पैरेंट एलिमेंट से एक सापेक्ष फ़ॉन्ट वजन भारी। |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | पैरेंट एलिमेंट से एक सापेक्ष फ़ॉन्ट वजन हल्का। |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | सामान्य फ़ॉन्ट वजन। 400 के समान। |

### संबंधित देखें

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
