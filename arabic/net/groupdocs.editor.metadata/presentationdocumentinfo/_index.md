---
title: "PresentationDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل البيانات الوصفية لمستند عرض تقديمي واحد"
type: docs
weight: 760
url: /ar/net/groupdocs.editor.metadata/presentationdocumentinfo/
---
## PresentationDocumentInfo structure

يمثل البيانات الوصفية لمستند عرض تقديمي واحد

```csharp
public struct PresentationDocumentInfo : IDocumentInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/presentationdocumentinfo/format) { get; } | يعيد تنسيق هذا المستند العرضي |
| [IsEncrypted](../../groupdocs.editor.metadata/presentationdocumentinfo/isencrypted) { get; } | يُشير إلى ما إذا كان هذا المستند العرضي المحدد مشفرًا ويتطلب كلمة مرور للفتح |
| [PageCount](../../groupdocs.editor.metadata/presentationdocumentinfo/pagecount) { get; } | يعيد عدد الشرائح في هذا المستند العرضي |
| [Size](../../groupdocs.editor.metadata/presentationdocumentinfo/size) { get; } | يعيد حجم هذا المستند العرضي بالبايت |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GeneratePreview](../../groupdocs.editor.metadata/presentationdocumentinfo/generatepreview)(int) | ينشئ ويعيد معاينة للشرائح المحددة على شكل صورة SVG |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
