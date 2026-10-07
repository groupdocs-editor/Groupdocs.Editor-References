---
title: "FontEmbeddingOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تتحكم خيارات تضمين الخطوط في الموارد الخطية التي يجب تضمينها في مستند WordProcessing أو PDF الناتج."
type: docs
weight: 880
url: /ar/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

تتحكم خيارات تضمين الخطوط في الموارد الخطية التي يجب تضمينها في مستند WordProcessing أو PDF الناتج.

```csharp
public enum FontEmbeddingOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| NotEmbed | `0` | لا تقم بدمج أي مورد خط ولا من EditableDocument ولا من النظام. القيمة الافتراضية. |
| EmbedAll | `1` | تحليل محتوى المستند من EditableDocument الإدخالي، العثور على جميع الخطوط المستخدمة ودمجها في مستند WordProcessing أو PDF الناتج. في المقام الأول يأخذ GroupDocs.Editor الخطوط من موارد الخط داخل EditableDocument. إذا كانت غير كافية أو مفقودة، فإن GroupDocs.Editor يأخذ الخطوط من نظام التشغيل. |
| EmbedWithoutSystem | `2` | مماثل لـ EmbedAll، لكن يستثني تلك الخطوط التي يعتبرها نظام التشغيل خطوطاً نظامية. |

### ملاحظات

يتم تطبيق خيارات دمج الخطوط أثناء حفظ المستند (من EditableDocument الوسيط إلى تنسيق WordProcessing أو PDF الناتج)، يتم تضمين هذا التعداد كخاصية في WordProcessingSaveOptions وPdfSaveOptions، حيث يجب استخدامه.

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
