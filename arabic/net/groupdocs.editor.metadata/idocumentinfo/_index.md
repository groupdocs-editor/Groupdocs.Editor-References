---
title: "IDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "واجهة مشتركة لجميع أغلفة البيانات الوصفية للملفات"
type: docs
weight: 740
url: /ar/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

واجهة مشتركة لجميع أغلفة البيانات الوصفية للملفات

```csharp
public interface IDocumentInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | في النوع المُنفذ يجب أن يُعيد تنسيق المستند كقيمة واحدة من نوع يمثل عائلة تنسيق واحدة ويرث من واجهة IDocumentFormat |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | يُشير إلى ما إذا كان الملف المحدد مشفرًا ويتطلب كلمة مرور للفتح. بالنسبة لأنواع المستندات التي لا يمكن تشفيرها (مثل جميع المستندات النصية) يجب دائمًا إرجاع 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | في النوع المُنفذ يجب أن يُعيد عدد (عدد) الصفحات أو الكيانات المشابهة المعتمدة على التنسيق (علامات التبويب، الشرائح، إلخ). بالنسبة لتلك العائلات التي لا تحتوي على شيء مشابه (مثل المستندات النصية العادية أو XML) يجب إرجاع 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | حجم المستند بالبايت |

### انظر أيضًا

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
