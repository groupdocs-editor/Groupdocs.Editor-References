---
title: TiffImage
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل صورة واحدة بتنسيق TIFF تنسيق ملف الصورة الموسوم ببياناته الوصفية والأساليب الإضافية
type: docs
weight: 560
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

يمثل صورة واحدة بتنسيق TIFF (تنسيق ملف الصورة الموسوم) ببياناته الوصفية والأساليب الإضافية

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | إنشاء مثيل GifImage جديد من المحتوى ، يتم تمثيله على شكل دفق بايت ، وباسم محدد |
| [TiffImage](tiffimage#constructor_1)(string, string) | إنشاء مثيل TiffImage جديد من المحتوى ، يتم تمثيله كسلسلة مشفرة باستخدام base64 ، وباسم محدد |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | إرجاع نسبة العرض إلى الارتفاع لهذه الصورة كعلاقة العرض إلى الارتفاع |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | إرجاع محتوى هذه الصورة النقطية على هيئة بايت stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | إرجاع اسم الملف الصحيح لهذه الصورة النقطية ، والتي تتكون من الاسم والامتداد. من الناحية النظرية يمكن أن تختلف عن الاسم. |
| [FramesCount](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/framescount) { get; } | يقوم بإرجاع عدد من الإطارات (الصور) داخل صورة TIFF هذه. لا يمكن أن يكون أقل من 1. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | يحدد ما إذا كان سيتم التخلص من هذه الصورة النقطية أم لا |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | إرجاع طول ملف الصورة النقطية بالبايت |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | إرجاع الأبعاد الخطية لهذه الصورة النقطية (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | إرجاع اسم هذه الصورة النقطية. عادة لا يحتوي على امتداد اسم الملف ويمكن نظريًا أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | إرجاع محتوى هذه الصورة النقطية كسلسلة بتشفير base64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | إرجاع ImageType. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | التخلص من هذه الصورة النقطية ، والتخلص من محتواها وجعل معظم الأساليب والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | التحقق من هذا المثيل بالمساواة المحددة في المرجع . |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | يولد ويعيد مثيلًا جديدًا لـ "System.Drawing.Bitmap" من هذه الصورة النقطية. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | لإنشاء وإرجاع مورد صورة جديد مخفض من نفس النوع ، ولكن بارتفاع مخفض جديد محدد وعرض مخفض نسبيًا . |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | يحفظ هذه الصورة النقطية في الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | للتحقق مما إذا كان الدفق المحدد صورة TIFF صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | للتحقق مما إذا كانت السلسلة المحددة بترميز base64 هي صورة TIFF صالحة |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | الحدث الذي يحدث عند التخلص من هذه الصورة النقطية |

### ملاحظات

راجع https://en.wikipedia.org/wiki/TIFF للحصول على التفاصيل. في حالات نادرة جدًا ، يكون TIFF موجودًا داخل مستندات معالجة الكلمات.

### أنظر أيضا

* class [RasterImageResourceBase](../rasterimageresourcebase)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
