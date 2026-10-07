---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحوّل المثيل المحدد QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype إلى الـ Char."
type: docs
weight: 100
url: /ar/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

يحوّل المثيل المحدد [`QuoteType`](../../quotetype) إلى الـ Char.

```csharp
public static explicit operator char(QuoteType quote)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| اقتباس | QuoteType | مثيل نوع الاقتباس للتحويل |

### انظر أيضًا

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

يحوّل الحرف Char المحدد إلى الـ [`QuoteType`](../../quotetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح.

```csharp
public static explicit operator QuoteType(char character)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| حرف | حرف | علامة اقتباس مفردة (U+0027 APOSTROPHE) أو علامة اقتباس مزدوجة (U+0022 QUOTATION MARK). سيتم إلقاء استثناء إذا تم تحديد أي حرف آخر. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | الحرف المحدد ليس علامة اقتباس أو فاصلة اقتباس مفردة |

### انظر أيضًا

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
