---
title: "op_Explicit"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype इंस्टेंस को Char में कास्ट करता है।"
type: docs
weight: 100
url: /hi/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

निर्दिष्ट [`QuoteType`](../../quotetype) इंस्टेंस को Char में कास्ट करता है।

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| कोट | QuoteType | कास्ट करने के लिए Quote प्रकार का इंस्टेंस |

### संबंधित देखें

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

विशिष्ट Char को संबंधित [`QuoteType`](../../quotetype) में कास्ट करता है, यदि कास्टिंग अमान्य हो तो अपवाद फेंकता है।

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| कैरेक्टर | अक्षर | एकल उद्धरण (U+0027 APOSTROPHE) या द्वि उद्धरण (U+0022 QUOTATION MARK) अक्षर। यदि कोई अन्य अक्षर निर्दिष्ट किया जाएगा तो अपवाद फेंका जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट Char उद्धरण चिह्न या अपोस्ट्रॉफ़ नहीं है। |

### संबंधित देखें

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
