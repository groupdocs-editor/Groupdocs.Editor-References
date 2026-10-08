---
title: "op_Explicit"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक स्ट्रिंग जो फ़ॉर्मेट फ़ैमिली नाम का प्रतिनिधित्व करती है, उसे FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase ऑब्जेक्ट में परिवर्तित करता है।"
type: docs
weight: 100
url: /hi/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

फ़ॉर्मेट फ़ैमिली नाम दर्शाने वाली स्ट्रिंग को एक [`FormatFamilyBase`](../../formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है।

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ैमिली | String | परिवर्तित करने के लिए फ़ॉर्मेट फ़ैमिली का नाम। |

### रिटर्न मान

निर्दिष्ट फ़ॉर्मेट फ़ैमिली नाम के अनुरूप एक [`FormatFamilyBase`](../../formatfamilybase) ऑब्जेक्ट।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | जब निर्दिष्ट फ़ॉर्मेट फ़ैमिली नाम अमान्य हो तो फेंका जाता है। |

### संबंधित देखें

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

फ़ॉर्मेट फ़ैमिली ID दर्शाने वाले पूर्णांक को एक [`FormatFamilyBase`](../../formatfamilybase) ऑब्जेक्ट में परिवर्तित करता है।

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| आईडी | Int32 | परिवर्तित करने के लिए फ़ॉर्मेट फ़ैमिली की आईडी। |

### रिटर्न मान

निर्दिष्ट फ़ॉर्मेट फ़ैमिली आईडी के अनुरूप एक [`FormatFamilyBase`](../../formatfamilybase) ऑब्जेक्ट।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | जब निर्दिष्ट फ़ॉर्मेट फ़ैमिली आईडी अमान्य हो तो फेंका जाता है। |

### संबंधित देखें

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
