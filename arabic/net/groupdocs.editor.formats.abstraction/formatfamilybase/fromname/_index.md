---
title: "FromName"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع كائنًا من النوع المحدد T الذي يملك الاسم المحدد."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

يسترجع نسخة من النوع المحدد *T* التي لها الاسم المحدد.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| معامل | الوصف |
| --- | --- |
| T | نوع عائلة الصيغة. |
| name | اسم عائلة الصيغة. |

### قيمة الإرجاع

كائن من النوع المحدد *T* مع الاسم المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما لا يتم العثور على عائلة صيغة مطابقة. |

### انظر أيضًا

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
