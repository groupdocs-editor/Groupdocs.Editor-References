---
title: "GeneratePreview"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ ويعيد معاينة للشرائح المحددة على شكل صورة SVG"
type: docs
weight: 50
url: /ar/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

ينشئ ويعيد معاينة للشرائح المحددة على شكل صورة SVG

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| slideIndex | Int32 | فهرس يبدأ من الصفر للشفرة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد الشرائح في هذا العرض. |

### قيمة الإرجاع

صورة SVG ككائن غير فارغ من الفئة [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | تم تحديد *slideIndex* أقل من 0 أو أكبر من عدد الشرائح في هذا العرض. |

### انظر أيضًا

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
