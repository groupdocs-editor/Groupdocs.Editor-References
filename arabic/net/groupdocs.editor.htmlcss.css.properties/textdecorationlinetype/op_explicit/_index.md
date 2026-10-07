---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحوّل Byte 8bit octet محدد إلى TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype المقابل، يرمي استثناءً إذا كان التحويل غير صالح"
type: docs
weight: 180
url: /ar/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

يحوّل Byte (8-bit octet) محدد إلى [`TextDecorationLineType`](../../textdecorationlinetype) المقابل، يرمي استثناءً إذا كان التحويل غير صالح

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| أوكتت | بايت | أوكتت 8-بت (حقل بت)، حيث أن الـ5 بتات الأولى صفر، بينما الـ3 بتات الأخيرة تشير إلى العلامات |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | القيمة المحددة لـ *octet* غير صالحة |

### انظر أيضًا

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

يحوّل المثيل المحدد من [`TextDecorationLineType`](../../textdecorationlinetype) إلى أوكتت مكافئ (حقل بت 8-بت)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| input | TextDecorationLineType | مثيل [`TextDecorationLineType`](../../textdecorationlinetype) للتحويل |

### انظر أيضًا

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
