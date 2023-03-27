---
title: Length
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: प्रतशत और इकई रहत प्रकर सहत कस भ सहयक इकई में CSS लंबई मन क प्रतनधत्व करत है मन पूर्णंक य फ़्लट ऋणत्मक शून्य और धनत्मक ह सकते हैं अपरवर्तनय संरचन.
type: docs
weight: 260
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

प्रतिशत और इकाई रहित प्रकार सहित किसी भी सहायक इकाई में CSS लंबाई मान का प्रतिनिधित्व करता है। मान पूर्णांक या फ़्लोट, ऋणात्मक, शून्य और धनात्मक हो सकते हैं। अपरिवर्तनीय संरचना.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | लंबाई आवृत्ति का फ़्लोट सांख्यिक मान लौटाता है। कभी अपवाद नहीं फेंकता - यदि आवश्यक हो तो पूर्णांक मान को फ्लोट में परिवर्तित करता है। |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | इस लंबाई उदाहरण का एक पूर्णांक संख्यात्मक मान लौटाता है, अगर इसे आंतरिक रूप से एक पूर्णांक के रूप में संग्रहीत किया जाता है, या एक अपवाद फेंकता है, अगर यह मूल रूप से फ्लोट नंबर के रूप में संग्रहीत किया गया था। |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | प्राप्त होता है यदि लंबाई निरपेक्ष इकाइयों में दी गई हो। इतनी लंबाई को पिक्सेल में बदला जा सकता है. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | इंगित करता है कि क्या इस लंबाई उदाहरण का संख्यात्मक मान मूल रूप से निर्दिष्ट किया गया था और फ्लोट (FP32) संख्या के रूप में संग्रहीत किया गया था |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | इंगित करता है कि क्या इस लंबाई उदाहरण का संख्यात्मक मान मूल रूप से निर्दिष्ट किया गया था और एक पूर्णांक (INT32) संख्या के रूप में संग्रहीत किया गया था |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | निर्धारित करता है कि क्या इस लंबाई का संख्यात्मक मान ऋणात्मक संख्या है |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | निर्धारित करता है कि क्या इस लंबाई का संख्यात्मक मान धनात्मक संख्या है |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | प्राप्त होता है यदि लंबाई सापेक्ष इकाइयों में दी गई हो। इतनी लंबाई को पिक्सेल में नहीं बदला जा सकता. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | मान में इकाई रहित प्रकार है, लेकिन शून्य नहीं है - धनात्मक या ऋणात्मक संख्या |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | निर्धारित करता है कि यह उदाहरण इकाई रहित शून्य है या नहीं। इकाई रहित शून्य इस प्रकार का डिफ़ॉल्ट मान है। IsDefault संपत्ति के समान। |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | निर्धारित करता है कि क्या इस लंबाई का संख्यात्मक मान शून्य संख्या है |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | इस लंबाई उदाहरण का एक इकाई प्रकार लौटाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | निर्दिष्ट डबल नंबर और यूनिट द्वारा लंबाई प्रकार का एक उदाहरण बनाता है और देता है |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | निर्दिष्ट फ्लोट नंबर और यूनिट द्वारा लंबाई प्रकार का एक उदाहरण बनाता है और देता है |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | निर्दिष्ट पूर्णांक संख्या और Unit द्वारा लंबाई प्रकार का एक उदाहरण बनाता है और देता है |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | निर्दिष्ट स्ट्रिंग को उसके संख्यात्मक मान और इकाई नाम सहित लंबाई मान के रूप में पार करता है और लौटाता है, या विफलता पर एक अपवाद फेंकता है |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | इस लंबाई उदाहरण की पूरी प्रति लौटाता है |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | परिभाषित करता है कि क्या यह मान अन्य निर्दिष्ट लंबाई के बराबर है |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | निर्धारित करता है कि क्या यह लंबाई निर्दिष्ट ऑब्जेक्ट के बराबर है |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | मूल्य और इकाई प्रकार के हैश-कोड को मिलाकर इस लंबाई उदाहरण के हैश-कोड की गणना और रिटर्न करता है |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | लंबाई मान को किसी अन्य इकाई प्रकार में परिवर्तित किए बिना, इस लंबाई का एक स्ट्रिंग प्रतिनिधित्व अपने मूल मूल रूप में लौटाता है (जैसा कि इसे संग्रहीत किया जाता है)। |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | यदि संभव हो तो लंबाई को दी गई इकाई में परिवर्तित करता है। यदि current या दी गई इकाई सापेक्ष है, तो एक अपवाद दिया जाएगा। |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | यदि संभव हो तो लंबाई को कई पिक्सेल में कनवर्ट करता है। यदि वर्तमान इकाई सापेक्ष है, तो एक अपवाद फेंका जाएगा। |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | निर्दिष्ट इकाई प्रकार में इस लंबाई का एक स्ट्रिंग प्रतिनिधित्व देता है। संख्यात्मक मान को इकाई प्रकार परिवर्तन के अनुरूप रूपांतरित किया जाएगा. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | निर्दिष्ट यूनिट नाम को पार्स करने का प्रयास करता है और यूनिट एनम के संबंधित मूल्य को वापस करता है। |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | एक निर्दिष्ट स्ट्रिंग को उसके संख्यात्मक मान और इकाई नाम सहित लंबाई मान के रूप में पार्स करने का प्रयास करता है |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | दो दी गई लंबाई की समानता की जाँच करता है। |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | दो दी गई लंबाई की असमानता की जाँच करता है। |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | दी गई लंबाई को दिए गए कारक पर गुणा करता है |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | इकाई रहित पूर्णांक शून्य - डिफ़ॉल्ट मान, डिफ़ॉल्ट पैरामीटर रहित कंस्ट्रक्टर के समान |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| enum [Unit](length.unit) | सभी समर्थित लंबाई इकाइयां |

### टिप्पणियों

इस प्रकार में अगले सीएसएस डेटा प्रकार शामिल हैं: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ सीएसएस/प्रतिशत

### यह सभी देखें

* interface [ICssDataType](../icssdatatype)
* नाम स्थान [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
