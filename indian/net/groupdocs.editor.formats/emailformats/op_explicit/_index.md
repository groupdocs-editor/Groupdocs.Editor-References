---
title: "op_Explicit"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक EmailFormatsgroupdocs.editor.formats/emailformats ऑब्जेक्ट में परिवर्तित करता है।"
type: docs
weight: 150
url: /hi/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [`EmailFormats`](../../emailformats) ऑब्जेक्ट में परिवर्तित करता है।

```csharp
public static explicit operator EmailFormats(string extension)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| एक्सटेंशन | String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हैं, तो अंतिम बिंदु के बाद वाला भाग उपयोग किया जाता है। |

### रिटर्न मान

निर्दिष्ट फ़ाइल एक्सटेंशन के अनुरूप एक [`EmailFormats`](../../emailformats) ऑब्जेक्ट।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [EmailFormats](../../emailformats) | जब निर्दिष्ट फ़ाइल एक्सटेंशन null हो तो उत्पन्न होता है। |

### संबंधित देखें

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
