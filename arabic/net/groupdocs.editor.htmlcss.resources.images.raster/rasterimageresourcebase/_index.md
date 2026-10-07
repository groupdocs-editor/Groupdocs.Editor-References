---
title: "RasterImageResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الفئة الأساسية لأي صورة نقطية مدعومة مع اسم ثابت، أبعاد، نسبة أبعاد، نوع، حجم ومحتوى."
type: docs
weight: 540
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

الفئة الأساسية لأي صورة نقطية مدعومة مع اسم ثابت، أبعاد، نسبة عرض إلى ارتفاع، نوع، حجم، ومحتوى.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | يعيد نسبة العرض إلى الارتفاع لهذه الصورة كعلاقة العرض إلى الارتفاع |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | يعيد محتوى هذه الصورة النقطية كتيار بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | يعيد اسم الملف الصحيح لهذه الصورة النقطية، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | يحدد ما إذا كانت هذه الصورة النقطية تم التخلص منها أم لا |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | يعيد طول ملف هذه الصورة النقطية بالبايت |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | يعيد الأبعاد الخطية لهذه الصورة النقطية (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | يعيد اسم هذه الصورة النقطية. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | يعيد محتوى هذه الصورة النقطية كسلسلة مشفرة بقاعدة64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | في النوع المنفذ يجب إرجاع معلومات حول نوع الصورة النقطية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | يحرر هذه الصورة النقطية، محرراً محتواها وجاعلاً معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | يحفظ هذه الصورة النقطية إلى الملف المحدد |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
