---
title: "IImageResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثّل مورد صورة من أي نوع، إما نقطية أو متجهة"
type: docs
weight: 470
url: /ar/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

يمثل مورد صورة من أي نوع، نقطية أو متجهة

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | في تنفيذ النوع يجب إرجاع نسبة العرض إلى الارتفاع لصورة معينة بغض النظر عن نوعها. كل من الصور المتجهة والنقطية لها نسبة عرض إلى ارتفاع داخلية بين عرضها وارتفاعها. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | في تنفيذ النوع يجب إرجاع الأبعاد الخطية للصورة. بالنسبة للصور النقطية تكون الأبعاد داخلية بوحدات البكسل. أما الصور المتجهة، فلا تمتلك أبعادًا ثابتة، لكن بياناتها الوصفية قد تحتوي على بعض الأبعاد الأساسية بوحدات قياس مختلفة. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | في تنفيذ النوع يجب إرجاع نوع صورة محددة ككائن من ImageType المحدد، الذي يضم جميع المعلومات الخاصة بالنوع. |

### ملاحظات

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### انظر أيضًا

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
