---
title: "WordProcessingDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل البيانات الوصفية لمستند معالجة نصوص واحد"
type: docs
weight: 790
url: /ar/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

يمثل البيانات الوصفية لمستند معالجة نصوص واحد

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | يعيد صيغة هذا المستند WordProcessing |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | يحدد ما إذا كان هذا المستند WordProcessing مشفرًا ويتطلب كلمة مرور للفتح |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | يعيد عدد الصفحات |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | يعيد الحجم بالبايت لهذا المستند WordProcessing |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | يحدد ما إذا كانت هذه الحالة مساوية للحالة المحددة الأخرى من نوع WordProcessingDocumentInfo |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | ينشئ ويعيد معاينة للصفحة المحددة في شكل صورة SVG |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
