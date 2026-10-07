---
title: "FontWeight"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "خاصية Fontweight تحدد وزن أو سمك الخط. الأوزان المتاحة تعتمد على عائلة الخط المحددة حاليًا."
type: docs
weight: 280
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

خاصية وزن الخط (font-weight) تحدد وزن الخط (أو سمكه). الأوزان المتاحة تعتمد على عائلة الخط المحددة حاليًا.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة مطلقة للوزن (السمك) للخط كعدد صحيح |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | يشير إلى ما إذا كان حجم الخط هذا لديه قيمة أولية (متوسط). |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة نسبية للوزن (السمك) للخط - مقارنةً بسمك العنصر الأب |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | يعيد رقمًا - قيمة صحيحة بين 1 و 1000، شاملة، تصف سمك الخط، أو يرمي استثناءً إذا كان السمك الحالي غير مطلق بل نسبي |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | يعيد قيمة هذا font-weight كسلسلة نصية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | ينشئ font-weight من رقم محدد |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | يحدد ما إذا كانت حالات FontWeight المحددة متساوية |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | يحدد ما إذا كانت حالة FontWeight هذه متساوية مع غير المصنفة المحددة |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | يعيد رمز تجزئة (hash-code) لهذه النسخة |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | يحاول تحليل سلسلة نصية محددة وإرجاع حالة FontWeight صالحة عند النجاح |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | يتحقق مما إذا كانت قيمتين "FontWeight" متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | يتحقق مما إذا كانت قيمتين "FontWeight" غير متساويتين |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | وزن الخط عريض. نفس 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | وزن خط نسبي واحد أثقل من العنصر الأب |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | وزن خط نسبي واحد أخف من العنصر الأب |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | وزن الخط عادي. نفس 400. |

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
