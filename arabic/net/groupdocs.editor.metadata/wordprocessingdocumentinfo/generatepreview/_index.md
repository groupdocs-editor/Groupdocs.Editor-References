---
title: "GeneratePreview"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ ويعيد معاينة للصفحة المحددة في شكل صورة SVG"
type: docs
weight: 60
url: /ar/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

ينشئ ويعيد معاينة للصفحة المحددة في شكل صورة SVG

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex | Int32 | فهرس يبدأ من الصفر للصفحة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد الصفحات في هذا المستند WordProcessing. |

### قيمة الإرجاع

صورة SVG ككائن غير فارغ من الفئة [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | تم تحديد *pageIndex* أقل من 0 أو أكبر من عدد الصفحات في هذا المستند WordProcessing. |

### انظر أيضًا

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
