---
title: FontSize
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: एक वशेष इकई य लंबई मन के रूप में फ़न्ट आकर क प्रतनधत्व करत है ज फ़न्ट के आकर क नर्दष्ट करत है ऐतहसक रूप से रजधन एम क चड़ई
type: docs
weight: 290
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

एक विशेष इकाई या लंबाई मान के रूप में फ़ॉन्ट आकार का प्रतिनिधित्व करता है, जो फ़ॉन्ट के आकार को निर्दिष्ट करता है (ऐतिहासिक रूप से राजधानी "एम" की चौड़ाई)।

```csharp
public struct FontSize : IEquatable<FontSize>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | इंगित करता है कि उपयोगकर्ता के डिफ़ॉल्ट फ़ॉन्ट आकार (जो मध्यम है) के आधार पर यह फ़ॉन्ट-आकार कीवर्ड के रूप में पूर्ण आकार के साथ परिभाषित किया गया है या नहीं |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | इंगित करता है कि क्या इस फ़ॉन्ट-आकार का प्रारंभिक मान है (मध्यम) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | इंगित करता है कि क्या यह फ़ॉन्ट-आकार एक के साथ परिभाषित किया गया है[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) मान |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | इंगित करता है कि क्या यह फ़ॉन्ट-आकार एक सापेक्ष आकार के साथ एक कीवर्ड के रूप में परिभाषित किया गया है। मूल तत्व के फ़ॉन्ट आकार के सापेक्ष फ़ॉन्ट बड़ा या छोटा होगा, मोटे तौर पर निरपेक्ष-आकार वाले कीवर्ड को अलग करने के लिए उपयोग किए जाने वाले अनुपात से. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | एक लंबाई मान, यदि यह फ़ॉन्ट-आकार इसके साथ परिभाषित किया गया था, या अन्यथा फेंक दिया गया अपवाद |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | इस फ़ॉन्ट आकार का मान string के रूप में लौटाता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | निर्दिष्ट लंबाई से फ़ॉन्ट-आकार बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | निर्धारित करता है कि क्या यह फ़ॉन्ट-आकार का उदाहरण निर्दिष्ट के बराबर है |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | निर्धारित करता है कि क्या यह फ़ॉन्ट-आकार का उदाहरण निर्दिष्ट uncasted के बराबर है |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | इस उदाहरण के लिए हैश-कोड लौटाता है |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | किसी निर्दिष्ट कीवर्ड को 'फ़ॉन्ट-साइज़' के उचित कीवर्ड मान के रूप में पहचानने का प्रयास करता है और इसे सफलता पर लौटाता है या विफलता पर NULL. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | जाँचता है कि क्या दो "FontSize" मान बराबर हैं |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | जाँचता है कि क्या दो "FontSize" मान बराबर नहीं हैं |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | सामान्य रूप से बड़ा निरपेक्ष-आकार |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | बड़ा सापेक्ष-आकार - फ़ॉन्ट मूल तत्व के फ़ॉन्ट-आकार के सापेक्ष बड़ा होगा, मोटे तौर पर उपरोक्त पूर्ण-आकार वाले कीवर्ड को अलग करने के लिए उपयोग किए गए अनुपात से। |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | मध्यम आकार। प्रारंभिक मूल्य. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | सामान्य रूप से छोटा निरपेक्ष-आकार |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | छोटे सापेक्ष-आकार - फ़ॉन्ट मूल तत्व के फ़ॉन्ट-आकार के सापेक्ष छोटा होगा, मोटे तौर पर उपरोक्त पूर्ण-आकार वाले कीवर्ड को अलग करने के लिए उपयोग किए जाने वाले अनुपात से। |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | औसत दर्जे का बड़ा निरपेक्ष-आकार |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | औसत दर्जे का छोटा निरपेक्ष-आकार |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | बहुत बड़ा निरपेक्ष-आकार |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | बहुत छोटा निरपेक्ष-आकार |

### यह सभी देखें

* नाम स्थान [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
