---
title: "MarkdownDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل البيانات الوصفية لمستند ماركداون واحد"
type: docs
weight: 750
url: /ar/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

يمثل البيانات الوصفية لمستند ماركداون واحد

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | يعيد تنسيق هذا المستند Markdown — دائمًا هو [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | نظرًا لأن مستندات Markdown لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | يعيد عدد الصفحات. عادةً لا تحتوي مستندات Markdown على صفحات ثابتة وبالتالي لا يوجد عدد صفحات، لذا يُحسب هذا الرقم بناءً على حجم الصفحة القياسي المحدد إلى A4 في وضعية عمودية. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | يعيد حجم هذا المستند Markdown بالبايت |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | يحدد ما إذا كانت هذه العينة مساوية للعينة الأخرى المحددة [`MarkdownDocumentInfo`](../markdowndocumentinfo). |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
