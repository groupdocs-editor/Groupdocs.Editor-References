---
title: "FromValue"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट पहचानकर्ता वाला निर्दिष्ट प्रकार T का एक उदाहरण प्राप्त करता है।"
type: docs
weight: 70
url: /hi/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

निर्दिष्ट प्रकार *T* की एक इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट पहचानकर्ता है।

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Parameter | विवरण |
| --- | --- |
| T | फ़ॉर्मेट फ़ैमिली का प्रकार। |
| value | फ़ॉर्मेट फ़ैमिली का पहचानकर्ता। |

### रिटर्न मान

निर्दिष्ट पहचानकर्ता वाला निर्दिष्ट प्रकार *T* का एक उदाहरण।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | जब कोई मेल खाने वाला फ़ॉर्मेट फ़ैमिली नहीं मिलता है तो फेंका जाता है। |

### संबंधित देखें

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
