---
title: "Ratio"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل نوع بيانات CSS ratio الذي يُستخدم لوصف نسب الأبعاد في استعلامات الوسائط وللصور النقطية عن طريق تحديد النسبة بين قيمتين بلا وحدة تسمى البسط والمقام. هيكل غير قابل للتغيير."
type: docs
weight: 250
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

يمثل نوع بيانات CSS "نسبة"، والذي يُستخدم لوصف نسب الأبعاد في استعلامات الوسائط وللصور النقطية عن طريق تحديد النسبة بين قيمتين بدون وحدة تُسمى "البسط" و"المقام". بنية غير قابلة للتغيير.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | يرجع مقام هذا ratio |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | يحدد ما إذا كان هذا ratio له قيمة افتراضية أو هو "1/1" (واحد) |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | يرجع بسط هذا ratio |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | ينشئ ويرجع نسخة واحدة من Ratio من البسط والمقام المحددين |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | يحسب ويرجع هذا ratio كعدد عائم واحد |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | يرجع نسخة كاملة من هذا ratio |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، والذي من المفترض أنه مثال آخر من "Ratio" |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | يحدد ما إذا كانت هذه الحالة مساوية للـ "Ratio" المحدد |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | يعيد رمز تجزئة لهذه النسخة، ولا يمكن تغييره خلال عمرها |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | ينتج ويرجع نسبة عكسية (متبادلة) لهذا ratio |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | يسلسل هذا ratio إلى سلسلة ويعيده |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | يرجع تمثيلًا نصيًا لهذا ratio؛ نفس "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | يقارن نسبتين ويرجع قيمة منطقية تشير إلى ما إذا كانتا متطابقتين. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانت النسبتان غير متطابقتين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | نسبة افتراضية واحدة 1/1 |

### ملاحظات

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### انظر أيضًا

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
