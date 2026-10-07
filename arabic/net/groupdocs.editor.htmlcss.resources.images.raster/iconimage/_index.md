---
title: "IconImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل صورة واحدة بتنسيق ICON مع بيانات التعريف الخاصة بها وطرق إضافية"
type: docs
weight: 510
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
## IconImage class

يمثل صورة واحدة بتنسيق ICON مع بيانات التعريف الخاصة بها وطرق إضافية

```csharp
public sealed class IconImage : RasterImageResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [IconImage](iconimage#constructor)(string, Stream) | ينشئ نسخة جديدة من IconImage من المحتوى الممثل كتيار بايت، وبالاسم المحدد |
| [IconImage](iconimage#constructor_1)(string, string) | ينشئ نسخة جديدة من IconImage من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وبالاسم المحدد |

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
| [NumberOfImages](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/numberofimages) { get; } | يعيد عدد الصور الموجودة في ملف ICON هذا |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | يعيد محتوى هذه الصورة النقطية كسلسلة مشفرة بقاعدة64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/type) { get; } | يرجع ImageType.Icon |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | يحرر هذه الصورة النقطية، محرراً محتواها وجاعلاً معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | يحفظ هذه الصورة النقطية إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/isvalid#isvalid)(Stream) | يتحقق مما إذا كان الدفق المحدد صورة ICON صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/isvalid#isvalid_1)(string) | يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة ICON صالحة |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
