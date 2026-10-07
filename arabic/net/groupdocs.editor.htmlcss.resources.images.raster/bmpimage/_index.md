---
title: "BmpImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل صورة واحدة بتنسيق BMP BitMap Picture مع بياناته الوصفية والطرق الإضافية"
type: docs
weight: 490
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
## BmpImage class

يمثل صورة واحدة بتنسيق BMP (صورة نقطية) مع بيانات التعريف الخاصة بها وطرق إضافية

```csharp
public sealed class BmpImage : RasterImageResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BmpImage](bmpimage#constructor)(string, Stream) | ينشئ نسخة جديدة من BmpImage من المحتوى الممثَّل كتيار بايت، ومع اسم محدد |
| [BmpImage](bmpimage#constructor_1)(string, string) | ينشئ نسخة جديدة من BmpImage من المحتوى الممثَّل كنص مشفر بقاعدة 64، ومع اسم محدد |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/type) { get; } | يرجع ImageType.Bmp |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | يحرر هذه الصورة النقطية، محرراً محتواها وجاعلاً معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | يحفظ هذه الصورة النقطية إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التيار المحدد صورة BMP صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid_1)(string) | يتحقق مما إذا كان النص المشفر بقاعدة 64 المحدد صورة BMP صالحة |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
