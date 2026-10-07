---
title: "ArgbColor"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل قيمة لون واحدة بتنسيق ARGB 32 بت، 8 بت لكل قناة بما في ذلك الشفافية، مع محولات ومسلسلات"
type: docs
weight: 160
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

يمثل قيمة لون واحدة بتنسيق ARGB 32-بت (8 بت لكل قناة بما في ذلك الشفافية) مع المحولات والمسلسلات

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | يحصل على الجزء ألفا من اللون. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | يحصل على الجزء ألفا من اللون كنسبة مئوية (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | يحصل على الجزء الأزرق من اللون. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | يحصل على الجزء الأخضر من اللون. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | يشير إلى ما إذا كانت هذه العينة [`ArgbColor`](../argbcolor) هي الافتراضية (Transparent) - جميع القنوات الأربعة مضبوطة على 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | لون غير مبدئ - جميع القنوات الأربعة مضبوطة على 0. نفس القيمة الافتراضية وTransparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | يشير إلى ما إذا كانت هذه العينة [`ArgbColor`](../argbcolor) غير شفافة تمامًا، بدون شفافية (قناة Alpha لها القيمة القصوى) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | يشير إلى ما إذا كانت هذه العينة [`ArgbColor`](../argbcolor) شفافة تمامًا - قناة Alpha لها القيمة الدنيا (0)، وبالتالي لا تؤثر القنوات R و G و B الأخرى بشكل مرئي. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | يشير إلى ما إذا كانت هذه العينة [`ArgbColor`](../argbcolor) شبه شفافة (ليست شفافة تمامًا، ولكنها ليست غير شفافة تمامًا) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | يحصل على الجزء الأحمر من اللون. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | يحصل على قيمة Int32 للون. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | ينشئ قيمة واحدة من [`ArgbColor`](../argbcolor) من القنوات الحمراء والخضراء والزرقاء المحددة، بينما قناة ألفا غير شفافة تمامًا |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | ينشئ قيمة واحدة من [`ArgbColor`](../argbcolor) من القنوات الحمراء والخضراء والزرقاء وقناة ألفا المحددة |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | ينشئ لونًا غير شفاف تمامًا (A=255) من قيمة واحدة، تُطبق على جميع القنوات |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | يفحص لونين من [`ArgbColor`](../argbcolor) للتساوي |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | يختبر ما إذا كان كائن آخر يساوي هذه الحالة من [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | يرجع رمز تجزئة يحدد اللون الحالي. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | يسلسل هذه الحالة من [`ArgbColor`](../argbcolor) إلى تدوين دالة CSS الأنسب حسب الشفافية |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | يسلسل هذه الحالة من [`ArgbColor`](../argbcolor) إلى تدوين دالة CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | يسلسل هذه الحالة من [`ArgbColor`](../argbcolor) إلى تدوين دالة CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | نفس ما في [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان متطابقين. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان غير متطابقين. |

## الأعضاء الآخرون

| الاسم | الوصف |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | يحتوي على جميع "الألوان المعروفة" التي لها اسم فريد ثابت وقيمة في معيار CSS |

### ملاحظات

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا على) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### انظر أيضًا

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
