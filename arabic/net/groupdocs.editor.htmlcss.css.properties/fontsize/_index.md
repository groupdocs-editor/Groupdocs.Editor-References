---
title: "FontSize"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل حجم الخط كوحدة خاصة أو قيمة طول تحدد حجم الخط تاريخيًا كعرض الحرف الكبير M."
type: docs
weight: 260
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

يمثل حجم الخط كوحدة خاصة أو قيمة طول، تحدد حجم الخط (تقليديًا عرض الحرف الكبير "M").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم مطلق ككلمة مفتاحية، بناءً على حجم الخط الافتراضي للمستخدم (الذي هو متوسط). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | يشير إلى ما إذا كان حجم الخط هذا لديه قيمة أولية (متوسط). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | يشير إلى ما إذا كان حجم الخط هذا معرفًا بقيمة [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم نسبي ككلمة مفتاحية. سيكون الخط أكبر أو أصغر بالنسبة إلى حجم خط العنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | قيمة طول، إذا تم تعريف حجم الخط هذا بها، أو يُرمى استثناءً خلاف ذلك. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | يرجع قيمة حجم الخط هذا كسلسلة نصية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | ينشئ حجم خط من طول محدد. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | يحدد ما إذا كانت نسخة حجم الخط هذه مساوية للمحددة. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | يحدد ما إذا كانت نسخة حجم الخط هذه مساوية للمحددة غير محوَّلة. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | يعيد رمز تجزئة (hash-code) لهذه النسخة |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة لـ 'font-size' وإرجاعها عند النجاح أو NULL عند الفشل. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | يتحقق مما إذا كانت قيمتي "FontSize" متساويتين. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | يتحقق مما إذا كانت قيمتي "FontSize" غير متساويتين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | الحجم المطلق الكبير عادةً. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | حجم نسبي أكبر - سيكون الخط أكبر بالنسبة إلى حجم خط العنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | حجم متوسط. القيمة الأولية. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | الحجم المطلق الصغير عادةً. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | حجم نسبي أصغر - سيكون الخط أصغر بالنسبة إلى حجم خط العنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | الحجم المطلق الكبير المتوسط. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | الحجم المطلق الصغير المتوسط. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | الحجم المطلق كبير جدًا. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | الحجم المطلق الصغير جدًا |

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
