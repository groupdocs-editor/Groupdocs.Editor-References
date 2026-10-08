---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट इकाई प्रकार में इस लंबाई का स्ट्रिंग प्रतिनिधित्व लौटाता है। संख्यात्मक मान इकाई प्रकार परिवर्तन के अनुसार परिवर्तित किया जाएगा।"
type: docs
weight: 260
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

निर्दिष्ट इकाई प्रकार में इस लंबाई का स्ट्रिंग प्रतिनिधित्व लौटाता है। संख्यात्मक मान इकाई प्रकार परिवर्तन के अनुसार परिवर्तित किया जाएगा।

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| unit | Unit | निर्दिष्ट इकाई, जिससे इस उदाहरण को स्ट्रिंग में सीरियलाइज़ करने से पहले परिवर्तित किया जाना चाहिए। यह मान्य होना चाहिए। इकाई रहित नहीं हो सकता। |

### रिटर्न मान

स्ट्रिंग प्रतिनिधित्व

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidEnumArgumentException | मान परिभाषित नहीं है |
| ArgumentOutOfRangeException | इकाई रहित मान निषिद्ध है |

### संबंधित देखें

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
