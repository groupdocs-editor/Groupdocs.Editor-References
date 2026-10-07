---
title: "ImageType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثّل تنسيق صورة مدعوم واحد يدعم كلًا من الصيغ النقطية والمتجهة"
type: docs
weight: 480
url: /ar/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

يمثل نوع صورة مدعوم واحد (تنسيق)، يدعم كل من الصيغ النقطية والمتجهة

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | نوع صورة BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | نوع صورة EMF (Enhanced MetaFile) المتجهة |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | نوع صورة GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | نوع صورة ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | نوع صورة JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | نوع صورة PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | نوع صورة متجهة SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | نوع صورة نقطية TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | نوع صورة غير معرف - قيمة خاصة، لا ينبغي أن تحدث عادةً |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | نوع صورة متجهة WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | امتداد الملف (بدون نقطة البداية) لنوع صورة معين بحروف صغيرة. بالنسبة للنوع غير المعرف يُعيد السلسلة 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | يعيد الاسم الرسمي لهذا التنسيق الصورة. لا يُعيد أبداً NULL. إذا كانت العينة غير تالفة، لا يرمي استثناءً. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | يشير إلى ما إذا كان هذا التنسيق معينًا متجهًا (true) أو نقطيًا (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | رمز MIME لنوع صورة معين كسلسلة. بالنسبة للنوع غير المعرف يُعيد السلسلة 'unsefined'. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | يعيد قيمة ImageType، التي تعادل امتداد اسم الملف المستخرج من اسم الملف المحدد |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | يعيد قيمة ImageType، التي تعادل رمز MIME المحدد |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | يحدد ما إذا كانت هذه العينة مساوية للعينة "ImageType" المحددة |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | يحدد ما إذا كانت هذه العينة مساوية للكيان غير المحول المحدد، والذي يُفترض أنه عينة أخرى من "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | يعيد رمز تجزئة (hash-code)، وهو رقم ثابت لهذه العينة المحددة |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | يعيد الخاصية FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | يحدد ما إذا كانت عينتين محددتين من ImageType متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | يحدد ما إذا كانت عينتين محددتين من ImageType غير متساويتين |

### انظر أيضًا

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
