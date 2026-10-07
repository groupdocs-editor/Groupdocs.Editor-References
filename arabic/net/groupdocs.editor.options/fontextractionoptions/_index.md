---
title: "FontExtractionOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تتحكم خيارات استخراج الخطوط في الخطوط التي يجب استخراجها ومن أين."
type: docs
weight: 890
url: /ar/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

تتحكم خيارات استخراج الخطوط في الخطوط التي يجب استخراجها ومن أين.

```csharp
public enum FontExtractionOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| NotExtract | `0` | لا يستخرج أي مورد خط ولا من المستند ولا من النظام. القيمة الافتراضية. |
| ExtractAllEmbedded | `1` | يستخرج جميع موارد الخطوط المضمنة في مستند Word الإدخالي، بغض النظر عن نوعها: مخصصة أو نظامية. |
| ExtractEmbeddedWithoutSystem | `2` | يستخرج فقط موارد الخطوط المضمنة التي هي مخصصة (ليس نظامية). |
| ExtractAll | `3` | يحاول استخراج جميع الخطوط المستخدمة في مستند WordProcessing الإدخالي، بما في ذلك الخطوط النظامية. |

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
