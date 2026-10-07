---
title: "XmlHighlightOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على خيارات تسمح بتخصيص تمييز XML أثناء تحويل XML إلى HTML"
type: docs
weight: 1290
url: /ar/net/groupdocs.editor.options/xmlhighlightoptions/
---
## XmlHighlightOptions class

يتضمن خيارات تسمح بتخصيص تمييز XML أثناء تحويل XML إلى HTML.

```csharp
public sealed class XmlHighlightOptions : IEditOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributeNamesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributenamesfontsettings) { get; } | مسؤول عن تمثيل خط أسماء السمات |
| [AttributeValuesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributevaluesfontsettings) { get; } | مسؤول عن تمثيل خط قيم السمات |
| [CDataFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/cdatafontsettings) { get; } | مسؤول عن تمثيل خط أقسام CDATA (بما في ذلك زوج العلامات الافتتاحية والختامية) |
| [HtmlCommentsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/htmlcommentsfontsettings) { get; } | مسؤول عن تمثيل خط تعليقات HTML (بما في ذلك زوج العلامات الافتتاحية والختامية) |
| [InnerTextFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/innertextfontsettings) { get; } | مسؤول عن تمثيل خط نص العلامة الداخلية |
| [IsDefault](../../groupdocs.editor.options/xmlhighlightoptions/isdefault) { get; } | يحدد ما إذا كان كائن خيارات تمييز XML هذا يحتوي على إعدادات الخط الافتراضية |
| [XmlTagsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/xmltagsfontsettings) { get; } | مسؤول عن تمثيل خط علامات XML (الأقواس الزاوية مع أسماء العلامات) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ResetToDefault](../../groupdocs.editor.options/xmlhighlightoptions/resettodefault)() | يعيد تعيين إعدادات الخط الحالية إلى قيمها الافتراضية |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
