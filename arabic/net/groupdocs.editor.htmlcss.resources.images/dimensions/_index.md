---
title: "الأبعاد"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل الأبعاد الخطية (العرض والارتفاع) لصورة نقطية مستطيلة واحدة بوحدة اختيارية. بنية غير قابلة للتغيير."
type: docs
weight: 450
url: /ar/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

يمثل الأبعاد الخطية (العرض والارتفاع) لصورة مستطيلة نقطية واحدة بوحدة عشوائية. بنية غير قابلة للتغيير.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | ينشئ عينة جديدة من العرض والارتفاع المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | يعيد عينة أبعاد فارغة |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | يعيد مساحة (العرض × الارتفاع) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | نسبة العرض إلى الارتفاع لهذه الأبعاد كالعرض/الارتفاع |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | يعيد ارتفاع الصورة. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | يحدد ما إذا كانت نسخة "Dimensions" هذه فارغة ومبدئية، أي أنها لا تخزن العرض والارتفاع الصحيحين |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | يحدد ما إذا كانت 'Dimensions' المحددة تمثل مربعًا، أي إذا كان العرض مساويًا للارتفاع |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | يعيد عرض الصورة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | يعيد نسخة كاملة من هذه النسخة |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | يحدد ما إذا كانت هذه النسخة مساوية لنسخة "Dimensions" المحددة |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | يحدد ما إذا كانت هذه النسخة مساوية لكائن غير محول محدد، والذي من المفترض أنه نسخة أخرى من "Dimensions" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | يعيد رمز تجزئة لهذه النسخة، ولا يمكن تغييره خلال عمرها |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | ينشئ ويعيد نسخة جديدة من "Dimensions"، يتم تغيير حجمها بشكل متناسب من الحالية بناءً على الارتفاع المحدد |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | ينشئ ويعيد نسخة جديدة من "Dimensions"، يتم تغيير حجمها بشكل متناسب من الحالية بناءً على العرض المحدد |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | يعيد تمثيلًا نصيًا لهذه "Dimensions" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | يفحص ما إذا كانت قيمتي "Dimensions" متساويتين، أي أن لهما نفس العرض والارتفاع، أو أن كلاهما فارغ |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | يفحص ما إذا كانت قيمتي "Dimensions" غير متساويتين، أي أن عرضهما أو ارتفاعهما المقابل مختلف |

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
