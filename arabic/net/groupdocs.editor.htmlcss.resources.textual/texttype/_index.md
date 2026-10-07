---
title: "TextType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل نوع مورد نصي قابل للدعم"
type: docs
weight: 640
url: /ar/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

يمثل نوع مورد نصي قابل للدعم

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | نوع CSS للمورد النصي |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | قيمة خاصة تشير إلى مورد نصي غير معرف أو غير معروف أو غير مدعوم |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | نوع XML للمورد النصي |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | امتداد الملف (بدون نقطة في البداية) لمورد نصي معين |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | يعيد الاسم الرسمي لهذا النوع من الموارد النصية |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | رمز MIME لنوع مورد نصي معين |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | يعيد قيمة TextType، التي تعادل امتداد اسم الملف، والتي يتم استخراجها من اسم الملف المحدد مع الامتداد أو الامتداد الصافي |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، والذي من المفترض أنه حالة "TextType" أخرى |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | يحدد ما إذا كانت هذه الحالة مساوية لحالة "TextType" المحددة |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | يعيد قيمة تجزئة (hash-code) وهي رقم ثابت لهذا النوع القيمي المحدد |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | يحدد ما إذا كانت حالتين محددتين من "TextType" متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | يحدد ما إذا كانت حالتين محددتين من "TextType" غير متساويتين |

### انظر أيضًا

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
