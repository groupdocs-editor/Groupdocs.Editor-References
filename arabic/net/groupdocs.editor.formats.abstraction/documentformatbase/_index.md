---
title: "DocumentFormatBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل الفئة الأساسية لتنسيقات المستند التي توفر وظائف مشتركة لنسخ التنسيق."
type: docs
weight: 50
url: /ar/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

يمثل الفئة الأساسية لصيغ المستندات، موفرًا وظائف مشتركة لحالات الصيغة.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة المحددة من [`FormatFamilyBase`](../formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة المحددة من [`IDocumentFormat`](../idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة المحددة من [`DocumentFormatBase`](../documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | يسترجع نسخة من النوع المحدد *T* التي لها نوع MIME المحدد. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | يحوّل نسخة من [`DocumentFormatBase`](../documentformatbase) إلى سلسلة بشكل ضمني. |

### انظر أيضًا

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
