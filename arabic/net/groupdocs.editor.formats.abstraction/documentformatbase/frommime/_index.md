---
title: "FromMime"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع كائنًا من النوع المحدد T الذي يمتلك نوع MIME المحدد."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

يسترجع نسخة من النوع المحدد *T* التي لها نوع MIME المحدد.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| معامل | الوصف |
| --- | --- |
| T | نوع تنسيق المستند. |
| mime | نوع MIME لتنسيق المستند. |

### قيمة الإرجاع

كائن من النوع المحدد *T* مع نوع MIME المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يُرمى عندما لا يتم العثور على تنسيق مستند مطابق. |

### انظر أيضًا

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
