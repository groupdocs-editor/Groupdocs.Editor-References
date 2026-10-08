---
title: "op_Explicit"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "विशिष्ट Byte 8bit octet को संबंधित TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype में कास्ट करता है, यदि कास्टिंग अमान्य हो तो अपवाद फेंकता है"
type: docs
weight: 180
url: /hi/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

विशिष्ट Byte (8-bit octet) को संबंधित [`TextDecorationLineType`](../../textdecorationlinetype) में कास्ट करता है, यदि कास्टिंग अमान्य हो तो अपवाद फेंकता है

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| ऑक्टेट | बाइट | एक 8-bit ऑक्टेट (बिटफ़ील्ड), जहाँ पहले 5 बिट शून्य होते हैं, जबकि अंतिम 3 फ़्लैग्स दर्शाते हैं |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट *octet* का मान अमान्य है |

### संबंधित देखें

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

निर्दिष्ट [`TextDecorationLineType`](../../textdecorationlinetype) इंस्टेंस को समकक्ष ऑक्टेट (8-bit बिटफ़ील्ड) में कास्ट करता है

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| input | TextDecorationLineType | [`TextDecorationLineType`](../../textdecorationlinetype) इंस्टेंस को कास्ट करने के लिए |

### संबंधित देखें

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
