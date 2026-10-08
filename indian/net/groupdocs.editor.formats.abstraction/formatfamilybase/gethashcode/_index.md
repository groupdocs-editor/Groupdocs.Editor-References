---
title: "GetHashCode"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

वर्तमान ऑब्जेक्ट के लिए हैश कोड लौटाता है।

```csharp
public override int GetHashCode()
```

### रिटर्न मान

वर्तमान ऑब्जेक्ट के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसे डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।

### टिप्पणियाँ

यह मेथड GetHashCode को ओवरराइड करता है। हैश कोड ऑब्जेक्ट की `Id` और `Name` प्रॉपर्टीज़ का उपयोग करके गणना किया जाता है। `unchecked` कॉन्टेक्स्ट ओवरफ़्लो की अनुमति देता है, जो हैश कोड गणना के संदर्भ में स्वीकार्य है।

### संबंधित देखें

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
