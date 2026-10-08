---
title: "TryParse"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट कीवर्ड को फ़ॉन्टस्टाइल के उचित कीवर्ड मान के रूप में पहचानने का प्रयास करता है और सफलता पर इसे लौटाता है या विफलता पर NULL लौटाता है।"
type: docs
weight: 80
url: /hi/net/groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse/
---
## FontStyle.TryParse method

निर्दिष्ट कीवर्ड को 'font-style' का उचित कीवर्ड वैल्यू मानने की कोशिश करता है और सफलता पर उसे लौटाता है या विफलता पर NULL लौटाता है।

```csharp
public static bool TryParse(string keyword, out FontStyle result)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| keyword | String | पार्स करने के लिए एक कीवर्ड |
| result | FontStyle& | परिणाम, यदि पार्सिंग सफल रही, अन्यथा [`Normal`](../normal) |

### रिटर्न मान

यदि पार्सिंग सफल रही तो true, अन्यथा false

### संबंधित देखें

* struct [FontStyle](../../fontstyle)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
