---
title: MarkdownDocumentInfo
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل البيانات الوصفية لوثيقة Markdown واحدة
type: docs
weight: 600
url: /ar/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

يمثل البيانات الوصفية لوثيقة Markdown واحدة

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | إرجاع تنسيق مستند Markdown هذا - دائمًا[`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | نظرًا لأنه لا يمكن تشفير مستندات Markdown بكلمة مرور ، تقوم هذه الخاصية دائمًا بإرجاع "false" |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | إرجاع عدد الصفحات. عادةً لا تحتوي مستندات Markdown على صفحات ثابتة وبالتالي عدد الصفحات ، لذلك يتم حساب هذا الرقم من حجم الصفحة القياسي المعين على A4 في الاتجاه الرأسي . |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | إرجاع الحجم بالبايت من مستند Markdown هذا |

## طُرق

| اسم | وصف |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | لتحديد ما إذا كان هذا المثيل يساوي الآخر المحدد[`MarkdownDocumentInfo`](../markdowndocumentinfo) المثال. |

### أنظر أيضا

* interface [IDocumentInfo](../idocumentinfo)
* مساحة الاسم [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->