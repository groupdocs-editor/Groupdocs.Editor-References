---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats."
type: docs
weight: 180
url: /ar/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن [`SpreadsheetFormats`](../../spreadsheetformats).

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`SpreadsheetFormats`](../../spreadsheetformats) المقابل لامتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
