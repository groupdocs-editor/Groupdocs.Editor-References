---
title: "MetaImageBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الفئة الأساسية المجردة لصيغ صور WMF وEMF"
type: docs
weight: 570
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

الفئة الأساسية المجردة لصيغ صور WMF وEMF

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | في النوع المُنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة كسلسلة بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | يحدد ما إذا كانت هذه الصورة النقطية مُتَخلَّص منها (`true`) أم لا (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | يرجع اسم هذه الصورة المتجهة. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | في النوع المُنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة بصيغة نصية: مشفر بقاعدة64 من XML المتعلق بنوع الصورة |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | في النوع المُنفذ يجب أن يُعيد معلومات حول نوع الصورة المتجهة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | في النوع المُنفذ يجب أن يُفرغ هذه النسخة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | في النوع المُنفذ يجب أن يحفظ هذه الصورة على القرص بالمسار المحدد |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | في النوع المُنفذ يجب أن يحفظ الصورة المتجهة الحالية بصيغة PNG النقطية في سلسلة البايت المحددة |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | عند تنفيذ نوع WMF أو EMF يجب حفظ الصورة المتجهة الحالية إلى تنسيق SVG المتجه إلى تدفق البايت المحدد |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### ملاحظات

هذه الفئة المجردة موروثة من قبل [`WmfImage`](../wmfimage) و [`EmfImage`](../emfimage)

### انظر أيضًا

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
