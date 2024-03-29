---
title: PngImage
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل صورة واحدة بتنسيق PNG رسومات الشبكة المحمولة مع البيانات الوصفية والأساليب الإضافية
type: docs
weight: 540
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
## PngImage class

يمثل صورة واحدة بتنسيق PNG (رسومات الشبكة المحمولة) مع البيانات الوصفية والأساليب الإضافية

```csharp
public sealed class PngImage : RasterImageResourceBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PngImage](pngimage#constructor)(string, Stream) | إنشاء مثيل PngImage جديد من المحتوى ، يتم تمثيله على هيئة دفق بايت ، وباسم محدد |
| [PngImage](pngimage#constructor_1)(string, string) | إنشاء مثيل PngImage جديد من المحتوى ، يتم تمثيله كسلسلة مشفرة باستخدام base64 ، وباسم محدد |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | إرجاع نسبة العرض إلى الارتفاع لهذه الصورة كعلاقة العرض إلى الارتفاع |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | إرجاع محتوى هذه الصورة النقطية على هيئة بايت stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | إرجاع اسم الملف الصحيح لهذه الصورة النقطية ، والتي تتكون من الاسم والامتداد. من الناحية النظرية يمكن أن تختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | يحدد ما إذا كان سيتم التخلص من هذه الصورة النقطية أم لا |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | إرجاع طول ملف الصورة النقطية بالبايت |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | إرجاع الأبعاد الخطية لهذه الصورة النقطية (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | إرجاع اسم هذه الصورة النقطية. عادة لا يحتوي على امتداد اسم الملف ويمكن نظريًا أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | إرجاع محتوى هذه الصورة النقطية كسلسلة بتشفير base64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/type) { get; } | إرجاع ImageType.Png |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | التخلص من هذه الصورة النقطية ، والتخلص من محتواها وجعل معظم الأساليب والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | التحقق من هذا المثيل بالمساواة المحددة في المرجع . |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | يولد ويعيد مثيلًا جديدًا لـ "System.Drawing.Bitmap" من هذه الصورة النقطية. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/reducetonewheight#reducetonewheight)(ushort) | لإنشاء وإرجاع صورة PNG جديدة مصغرة ، ولكن بارتفاع مخفض جديد محدد وعرض مخفض نسبيًا . (2 methods) |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | يحفظ هذه الصورة النقطية في الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid)(Stream) | للتحقق مما إذا كان الدفق المحدد صورة PNG صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid_1)(string) | للتحقق مما إذا كانت السلسلة المحددة بترميز base64 هي صورة PNG صالحة |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | الحدث الذي يحدث عند التخلص من هذه الصورة النقطية |

### أنظر أيضا

* class [RasterImageResourceBase](../rasterimageresourcebase)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
