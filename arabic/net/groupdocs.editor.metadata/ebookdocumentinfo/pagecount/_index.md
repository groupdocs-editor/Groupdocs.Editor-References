---
title: PageCount
second_title: GroupDocs.Editor لمرجع .NET API
description: يعرض عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub .
type: docs
weight: 30
url: /ar/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

يعرض عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub .

```csharp
public int PageCount { get; }
```

### ملاحظات

لا تحتوي مستندات الكتاب الإلكتروني عادةً على صفحات ثابتة وبالتالي عدد الصفحات. في حالة ePub ، من الممكن حساب عدد من الفصول. ومع ذلك ، لا تحتوي تنسيقات MOBI و AZW3 على فصول أيضًا ، لذلك يتم حساب هذا الرقم من حجم الصفحة القياسي المعين على A4 في الاتجاه الرأسي.

### أنظر أيضا

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* مساحة الاسم [GroupDocs.Editor.Metadata](../../ebookdocumentinfo)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->