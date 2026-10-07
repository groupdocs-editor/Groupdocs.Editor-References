---
title: "SvgImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل صورة متجهة واحدة بصيغة SVG Scalable Vector Graphics مع أبعاد البيانات الوصفية الخاصة بها وطرق إضافية لحفظها كـ PNG"
type: docs
weight: 580
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

يمثل صورة متجهة واحدة بصيغة SVG (رسومات متجهية قابلة للتوسيع) مع بياناتها الوصفية (الأبعاد) والطرق الإضافية (حفظ إلى PNG).

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | ينشئ كائن SvgImage جديد من المحتوى، الممثل كتيار بايت، ومع اسم محدد |
| [SvgImage](svgimage#constructor_1)(string, string) | ينشئ كائن SvgImage جديد من المحتوى، الممثل كسلسلة نصية عادية، ومع اسم محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | يعيد محتوى صورة SVG هذه كتيار ثنائي مع الموضع الأصلي |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | يحدد ما إذا كانت هذه الصورة النقطية مُتَخلَّص منها (`true`) أم لا (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | يرجع اسم هذه الصورة المتجهة. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | يعيد محتوى صورة SVG هذه كمحتوى ثنائي مشفر بقاعدة64 (ليس كنص خام بصيغة XML) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | يعيد [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | يعيد محتوى صورة SVG هذه بصيغتها النصية المتوافقة مع XML الأصلية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | يحرر هذه الصورة النقطية، محرراً محتواها وجاعلاً معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | يحفظ صورة SVG هذه إلى الملف |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | يحفظ صورة SVG المتجهة هذه كصورة PNG نقطية |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | يجري فحصًا سطحيًا لمعرفة ما إذا كان المحتوى النصي المتوافق مع XML المحدد يمثل صورة SVG |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
