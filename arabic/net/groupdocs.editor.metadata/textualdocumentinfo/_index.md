---
title: "TextualDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل بيانات التعريف لوثيقة نصية واحدة مثل XML HTML أو نص عادي TXT"
type: docs
weight: 780
url: /ar/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

يمثل البيانات الوصفية لمستند نصي واحد مثل XML أو HTML أو نص عادي (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | يعيد الترميز المكتشف المحتمل للمستند النصي |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | يعيد تنسيق هذا المستند النصي. قد لا يكون صحيحًا بنسبة 100٪ في بعض الحالات. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | دائمًا يعيد ``false``، لأن المستندات النصية لا يمكن تشفيرها |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | دائمًا يعيد 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | يعيد الحجم بالبايت (ليس عدد الأحرف) لهذا المستند النصي |

### انظر أيضًا

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
