---
title: "FontType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل نوع خط واحد مدعوم"
type: docs
weight: 360
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

يمثل نوع خط واحد مدعوم

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | يمثل نوع خط EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | يمثل نوع خط OTF (OpenType Font) |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | يمثل خط مجموعة TrueType (TTC) |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | يمثل نوع خط TTF (TrueType Font) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | قيمة خاصة، تُشير إلى مورد خط غير معرف أو غير معروف أو غير مدعوم |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | يمثل نوع خط WOFF (Web Open Font Format) |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | يمثل نوع خط WOFF2 (Web Open Font Format الإصدار 2) |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | يرجع اسمًا متوافقًا مع CSS لهذا النوع من الخطوط، يُستخدم في قاعدة @font-face |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | امتداد اسم الملف (بدون علامة النقطة) لهذا النوع من الخطوط |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | تنسيق الخط لتنسيق @font-face |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | يرجع اسمًا رسميًا لهذا النوع من الخطوط |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | رمز MIME لنوع خط معين |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | يرجع أول نوع خط من المجموعة المحددة لا يكون قيمة "Undefined"، أو نوع الخط "Undefined" إذا كانت جميع العناصر "Undefined" |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | يرجع قيمة FontType التي تعادل الاسم المتوافق مع CSS المحدد لنوع الخط |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | يرجع قيمة FontType التي تعادل امتداد اسم الملف المستخرج من اسم الملف المحدد |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | يرجع قيمة FontType التي تعادل رمز MIME المحدد |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | يحدد ما إذا كانت هذه العينة مساوية للنسخة "FontType" المحددة |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | يحدد ما إذا كانت هذه العينة مساوية للعنصر غير المحول المحدد، والذي يُفترض أنه نسخة أخرى من "FontType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | يعيد قيمة تجزئة (hash-code) وهي رقم ثابت لهذا النوع القيمي المحدد |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | يتحقق مما إذا كانت قيمتي "FontType" متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | يتحقق مما إذا كانت قيمتي "FontType" غير متساويتين |

### انظر أيضًا

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
