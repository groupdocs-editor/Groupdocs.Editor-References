---
title: "PageCount"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub."
type: docs
weight: 30
url: /ar/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

يرجع عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub.

```csharp
public int PageCount { get; }
```

### ملاحظات

عادةً ما لا تحتوي مستندات e-Book على صفحات ثابتة وبالتالي لا يوجد عدد صفحات. في حالة ePub يمكن حساب عدد الفصول. ومع ذلك، لا تحتوي صيغ MOBI و AZW3 على فصول أيضًا، لذا يتم حساب هذا العدد بناءً على حجم الصفحة القياسي المحدد إلى A4 في الوضع العمودي.

### انظر أيضًا

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
