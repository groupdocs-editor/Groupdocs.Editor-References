---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن TextualFormatsgroupdocs.editor.formats/textualformats."
type: docs
weight: 100
url: /ar/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن [`TextualFormats`](../../textualformats).

```csharp
public static explicit operator TextualFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`TextualFormats`](../../textualformats) يتوافق مع امتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [TextualFormats](../../textualformats) | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
