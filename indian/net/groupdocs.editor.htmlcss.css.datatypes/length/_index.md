---
title: "लंबाई"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "किसी भी समर्थित इकाई, जिसमें प्रतिशत और इकाई‑रहित प्रकार शामिल हैं, में CSS लंबाई मान का प्रतिनिधित्व करता है। मान पूर्णांक या फ्लोट, नकारात्मक शून्य और सकारात्मक हो सकते हैं। अपरिवर्तनीय संरचना।"
type: docs
weight: 230
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

किसी भी समर्थित इकाई में CSS लंबाई मान का प्रतिनिधित्व करता है, जिसमें प्रतिशत और बिना इकाई वाला प्रकार शामिल है। मान पूर्णांक या फ्लोट, नकारात्मक, शून्य और सकारात्मक हो सकते हैं। अपरिवर्तनीय संरचना।

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Length इंस्टेंस का फ्लोट संख्यात्मक मान लौटाता है। कभी भी अपवाद नहीं फेंकता - आवश्यक होने पर पूर्णांक मान को फ्लोट में परिवर्तित करता है। |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | यदि यह आंतरिक रूप से पूर्णांक के रूप में संग्रहीत है तो इस Length इंस्टेंस का पूर्णांक संख्यात्मक मान लौटाता है, या यदि मूल रूप से फ्लोट संख्या के रूप में संग्रहीत था तो अपवाद फेंकता है। |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | जाँचता है कि क्या लंबाई निरपेक्ष इकाइयों में दी गई है। ऐसी लंबाई को पिक्सेल में परिवर्तित किया जा सकता है। |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | यह दर्शाता है कि इस Length इंस्टेंस का डिफ़ॉल्ट मान — इकाई‑रहित शून्य है। IsUnitlessZero प्रॉपर्टी के समान। |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | यह दर्शाता है कि इस Length इंस्टेंस का संख्यात्मक मान मूल रूप से फ्लोट (FP32) संख्या के रूप में निर्दिष्ट और संग्रहीत था या नहीं। |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | यह दर्शाता है कि इस Length इंस्टेंस का संख्यात्मक मान मूल रूप से पूर्णांक (INT32) संख्या के रूप में निर्दिष्ट और संग्रहीत था या नहीं। |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान नकारात्मक संख्या है या नहीं। |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान सकारात्मक संख्या है या नहीं। |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | जाँचता है कि क्या लंबाई सापेक्ष इकाइयों में दी गई है। ऐसी लंबाई को पिक्सेल में परिवर्तित नहीं किया जा सकता। |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | मान का प्रकार इकाई‑रहित है, लेकिन यह शून्य नहीं है — यह सकारात्मक या नकारात्मक संख्या है। |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | निर्धारित करता है कि यह इंस्टेंस इकाई‑रहित शून्य है या नहीं। इकाई‑रहित शून्य इस प्रकार का डिफ़ॉल्ट मान है। IsDefault प्रॉपर्टी के समान। |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | निर्धारित करता है कि इस लंबाई का संख्यात्मक मान शून्य संख्या है या नहीं। |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | इस Length इंस्टेंस का इकाई प्रकार लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | निर्दिष्ट डबल संख्या और इकाई द्वारा Length प्रकार का एक इंस्टेंस बनाता और लौटाता है। |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | निर्दिष्ट फ्लोट संख्या और इकाई द्वारा Length प्रकार का एक इंस्टेंस बनाता और लौटाता है। |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | निर्दिष्ट पूर्णांक संख्या और इकाई द्वारा Length प्रकार का एक इंस्टेंस बनाता और लौटाता है। |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करता है और लौटाता है, जिसमें उसका संख्यात्मक मान और इकाई नाम शामिल है, या विफलता पर अपवाद फेंकता है। |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | इस Length इंस्टेंस की पूरी प्रतिलिपि लौटाता है। |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | परिभाषित करता है कि यह मान अन्य निर्दिष्ट लंबाई के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | निर्धारित करता है कि यह लंबाई निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | मान और इकाई प्रकार के हैश‑कोड को मिलाकर इस Length इंस्टेंस का हैश‑कोड गणना करता है और लौटाता है। |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | इस लंबाई का स्ट्रिंग प्रतिनिधित्व उसकी मूल मूल रूप में (जैसे यह संग्रहीत है) लौटाता है, बिना लंबाई मान को किसी अन्य इकाई प्रकार में परिवर्तित किए। |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | यदि संभव हो तो लंबाई को दिए गए इकाई में परिवर्तित करता है। यदि वर्तमान या दिया गया इकाई सापेक्ष है, तो अपवाद फेंका जाएगा। |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | यदि संभव हो तो लंबाई को पिक्सेल की संख्या में परिवर्तित करता है। यदि वर्तमान इकाई सापेक्ष है, तो अपवाद फेंका जाएगा। |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | निर्दिष्ट इकाई प्रकार में इस लंबाई का स्ट्रिंग प्रतिनिधित्व लौटाता है। संख्यात्मक मान इकाई प्रकार परिवर्तन के अनुसार परिवर्तित किया जाएगा। |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | निर्दिष्ट इकाई नाम को पार्स करने का प्रयास करता है और Unit enum का संबंधित मान लौटाता है। यदि उपयुक्त इकाई नहीं मिलती है तो Unit.Unitless लौटाता है। |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करने का प्रयास करता है, जिसमें उसका संख्यात्मक मान और इकाई नाम शामिल है। |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | दिए गए दो लंबाइयों की समानता की जाँच करता है। |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | दिए गए दो लंबाइयों की असमानता की जाँच करता है। |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | दिए गए Length को दिए गए गुणक से गुणा करता है। |

## फ़ील्ड

| नाम | विवरण |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Unitless पूर्णांक शून्य - डिफ़ॉल्ट मान, डिफ़ॉल्ट पैरामीटररहित कन्स्ट्रक्टर के समान। |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| enum [Unit](length.unit) | सभी समर्थित लंबाई इकाइयाँ |

### टिप्पणियाँ

यह प्रकार निम्नलिखित CSS डेटा प्रकारों को कवर करता है: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### संबंधित देखें

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
