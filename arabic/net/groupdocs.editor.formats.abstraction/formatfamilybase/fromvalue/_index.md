---
title: "FromValue"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع كائنًا من النوع المحدد T الذي يملك المعرف المحدد."
type: docs
weight: 70
url: /ar/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

يسترجع نسخة من النوع المحدد *T* التي لها المعرف المحدد.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| معامل | الوصف |
| --- | --- |
| T | نوع عائلة الصيغة. |
| value | معرّف عائلة الصيغة. |

### قيمة الإرجاع

كائن من النوع المحدد *T* مع المعرف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما لا يتم العثور على عائلة صيغة مطابقة. |

### انظر أيضًا

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
