---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ॉर्मेट परिवारों के लिए बेस क्लास को दर्शाता है जो फ़ॉर्मेट परिवार इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

फ़ॉर्मैट परिवारों के लिए बेस क्लास का प्रतिनिधित्व करता है, जो फ़ॉर्मैट परिवार इंस्टेंस के लिए सामान्य कार्यक्षमता प्रदान करता है।

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | फ़ॉर्मेट फैमिली के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | फ़ॉर्मेट फैमिली का नाम प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस के बराबर है या नहीं। |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | निर्दिष्ट प्रकार *T* की एक इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट नाम है। |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | निर्दिष्ट प्रकार *T* की एक इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट पहचानकर्ता है। |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | निर्दिष्ट प्रकार *T* की सभी इंस्टेंस प्राप्त करता है जो [`FormatFamilyBase`](../formatfamilybase) से व्युत्पन्न हैं। |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | निर्धारित करता है कि दो [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस बराबर हैं या नहीं। (2 ऑपरेटर) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | फ़ॉर्मेट परिवार नाम का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`FormatFamilyBase`](../formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है। (2 ऑपरेटर) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | एक [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस को अप्रत्यक्ष रूप से पूर्णांक में परिवर्तित करता है। (2 ऑपरेटर) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | निर्धारित करता है कि दो [`FormatFamilyBase`](../formatfamilybase) इंस्टेंस असमान हैं या नहीं। (2 ऑपरेटर) |

### टिप्पणियाँ

यह क्लास एब्स्ट्रैक्ट है और इसे एक व्युत्पन्न क्लास द्वारा विरासत में लेना आवश्यक है जो वास्तविक फ़ॉर्मेट परिवार विवरण निर्दिष्ट करती है।

### संबंधित देखें

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
