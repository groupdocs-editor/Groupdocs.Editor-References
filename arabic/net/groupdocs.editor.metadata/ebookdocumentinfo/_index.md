---
title: "EbookDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل البيانات التعريفية لمستند eBook واحد"
type: docs
weight: 710
url: /ar/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

يمثل البيانات الوصفية لمستند كتاب إلكتروني واحد

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | يعيد صيغة هذا e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | نظرًا لأنه لا يمكن تشفير مستندات e-Book بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | يرجع عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | يرجع حجم هذا المستند الإلكتروني بالبايت. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | يحدد ما إذا كانت هذه الحالة مساوية للحالة المحددة الأخرى من EbookDocumentInfo. |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
