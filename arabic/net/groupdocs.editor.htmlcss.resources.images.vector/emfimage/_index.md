---
title: "EmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تمثل صورة متجهة واحدة في تنسيق Enhanced Metafile EMF مع بياناتها الوصفية والطرق الإضافية"
type: docs
weight: 560
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

يمثل صورة متجهة واحدة بصيغة ملف ميتا محسن (EMF) مع بياناتها الوصفية والطرق الإضافية.

```csharp
public sealed class EmfImage : MetaImageBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | ينشئ نسخة جديدة من EmfImage من المحتوى الممثل كتدفق بايت، وبالاسم المحدد |
| [EmfImage](emfimage#constructor_1)(string, string) | ينشئ نسخة جديدة من EmfImage من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وبالاسم المحدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | يرجع محتوى هذه الصورة EMF كتدفق ثنائي |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | يحدد ما إذا كانت هذه الصورة النقطية مُتَخلَّص منها (`true`) أم لا (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | يرجع اسم هذه الصورة المتجهة. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | يرجع محتوى هذه الصورة EMF كنص عادي |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | يرجع ImageType.Emf |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | يتخلص من هذه الصورة EMF عن طريق تحرير محتواها وجعل معظم طرقها وخصائصها غير عاملة. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | يحفظ هذه الصورة EMF إلى الملف |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | يحفظ هذه الصورة المتجهة EMF كصورة PNG نقطية |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | يحفظ صورة EMF المتجهة هذه كصورة SVG متجهة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التيار المحدد صورة EMF صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | يتحقق مما إذا كان النص المشفر بقاعدة64 المحدد صورة EMF صالحة |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
