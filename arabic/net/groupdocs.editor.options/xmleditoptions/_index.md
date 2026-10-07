---
title: "XmlEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لتحرير مستندات XML (لغة الترميز القابلة للتوسيع) وتحويلها إلى HTML"
type: docs
weight: 1270
url: /ar/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

يسمح بتحديد خيارات مخصصة لتحرير مستندات XML (لغة الترميز القابلة للتوسيع) وتحويلها إلى HTML.

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | يسمح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمات. الاقتباسات المزدوجة هي الافتراضية. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | ترميز الأحرف لمستند النص، والذي سيُطبق عند فتحه. بشكل افتراضي يكون null — سيتم تطبيق ترميز المستند الداخلي. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | يسمح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة. يكون معطلًا بشكل افتراضي (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | يسمح بضبط تنسيق XML الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. يتم استخدام التنسيق الافتراضي ويمكن تعديله. لا يمكن أن يكون فارغًا. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | يسمح بضبط تمييز XML الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. يتم استخدام تمييز افتراضي ويمكن تعديله. لا يمكن أن يكون فارغًا. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | يسمح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في قيم السمات |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | يسمح بتمكين خوارزمية التعرف على URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | يسمح بتمكين قطع المسافات البيضاء المتتبعة في نص العلامة الداخلية. يكون معطلاً افتراضيًا (false) — ستُحفظ المسافات البيضاء المتتبعة. |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
