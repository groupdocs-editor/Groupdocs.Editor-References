---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل اسم عائلة تنسيق إلى كائن FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase."
type: docs
weight: 100
url: /ar/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

يقوم بتحويل سلسلة تمثل اسم عائلة تنسيق إلى كائن [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| family | String | اسم عائلة التنسيق للتحويل. |

### قيمة الإرجاع

كائن [`FormatFamilyBase`](../../formatfamilybase) المقابل لاسم عائلة التنسيق المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون اسم عائلة التنسيق المحدد غير صالح. |

### انظر أيضًا

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

يقوم بتحويل عدد صحيح يمثل معرّف عائلة التنسيق إلى كائن [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| id | Int32 | معرّف عائلة التنسيق للتحويل. |

### قيمة الإرجاع

كائن [`FormatFamilyBase`](../../formatfamilybase) المقابل لمعرّف عائلة التنسيق المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون معرّف عائلة التنسيق المحدد غير صالح. |

### انظر أيضًا

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
