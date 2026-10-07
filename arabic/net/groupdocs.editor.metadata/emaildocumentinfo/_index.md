---
title: "EmailDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل البيانات الوصفية لمستند بريد إلكتروني واحد بأي تنسيق بريد إلكتروني مدعوم"
type: docs
weight: 720
url: /ar/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

يمثل البيانات الوصفية لمستند بريد إلكتروني واحد بأي تنسيق بريد إلكتروني مدعوم

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | يعيد صيغة هذا المستند email |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | نظرًا لأنه لا يمكن تشفير مستندات البريد الإلكتروني بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | دائمًا تُعيد 1، لأن مستندات البريد الإلكتروني لا تحتوي على عرض صفحات |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | يعيد الحجم بالبايت لهذا المستند email |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | يحدد ما إذا كانت هذه الحالة مساوية للحالة المحددة الأخرى من نوع EmailDocumentInfo |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
