---
title: "WmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تمثل صورة متجهة واحدة في تنسيق WMF Windows MetaFile مع بياناتها الوصفية والطرق الإضافية"
type: docs
weight: 600
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

يمثل صورة متجهة واحدة بصيغة WMF (ملف ميتا ويندوز) مع بياناتها الوصفية والطرق الإضافية.

```csharp
public sealed class WmfImage : MetaImageBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | ينشئ نسخة جديدة من WmfImage من المحتوى الممثل كتدفق بايت، وبالاسم المحدد |
| [WmfImage](wmfimage#constructor_1)(string, string) | ينشئ نسخة جديدة من WmfImage من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وبالاسم المحدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | يرجع محتوى هذه الصورة WMF كتدفق ثنائي |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | يحدد ما إذا كانت هذه الصورة النقطية مُتَخلَّص منها (`true`) أم لا (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | يرجع اسم هذه الصورة المتجهة. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | يرجع محتوى هذه الصورة WMF كنص عادي |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | يرجع ImageType.Wmf |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | يتخلص من هذه الصورة WMF عن طريق تحرير محتواها وجعل معظم طرقها وخصائصها غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | يفحص هذه النسخة مع المحدد على مساواة المرجع. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | يحفظ هذه الصورة WMF إلى الملف |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | يحفظ هذه الصورة المتجهة WMF كصورة PNG نقطية |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | يحفظ هذه الصورة المتجهة WMF كصورة SVG متجهة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التدفق المحدد صورة WMF صالحة |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة صورة WMF صالحة |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | حدث يحدث عندما يتم إفراغ هذه الصورة النقطية |

### انظر أيضًا

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
