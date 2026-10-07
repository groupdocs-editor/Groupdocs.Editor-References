---
title: "GeneratePreview"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ ويعيد معاينة للورقة المحددة في شكل صورة SVG"
type: docs
weight: 60
url: /ar/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

ينشئ ويعيد معاينة للورقة المحددة في شكل صورة SVG

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| worksheetIndex | Int32 | فهرس يبدأ من الصفر للورقة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد أوراق العمل في هذه جدول البيانات. |

### قيمة الإرجاع

صورة SVG ككائن غير فارغ من الفئة [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | تم تحديد *worksheetIndex* أقل من 0 أو أكبر من عدد أوراق العمل في هذه جدول البيانات. |

### انظر أيضًا

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
