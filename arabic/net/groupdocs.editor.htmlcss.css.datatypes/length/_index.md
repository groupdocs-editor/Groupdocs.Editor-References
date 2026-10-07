---
title: "الطول"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل قيمة طول CSS بأي وحدة مدعومة بما في ذلك النسبة المئوية والنوع بدون وحدة. قد تكون القيم عددًا صحيحًا أو عائمًا سالبًا أو صفرًا أو موجبًا. بنية غير قابلة للتغيير."
type: docs
weight: 230
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

يمثل قيمة طول CSS بأي وحدة مدعومة، بما في ذلك النسبة المئوية والنوع بدون وحدة. قد تكون القيم عددًا صحيحًا أو عشريًا، سلبية، صفرية أو إيجابية. بنية غير قابلة للتغيير.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | يرجع قيمة عددية عائمة من كائن Length. لا يرمي استثناءً أبدًا - يحول القيمة الصحيحة إلى عائمة إذا لزم الأمر. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | يرجع قيمة عددية صحيحة لهذا الكائن Length إذا تم تخزينها داخليًا كعدد صحيح، أو يرمي استثناءً إذا كانت مخزنة أصلاً كعدد عائم. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | يحدد ما إذا كان الطول معطى بوحدات مطلقة. يمكن تحويل مثل هذا الطول إلى بكسلات. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | يشير إلى ما إذا كان كائن Length هذا يمتلك قيمة افتراضية — صفر بدون وحدة. نفس خاصية IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | يشير إلى ما إذا كانت القيمة العددية لهذا الكائن Length قد تم تحديدها وتخزينها أصلاً كعدد عائم (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | يشير إلى ما إذا كانت القيمة العددية لهذا الكائن Length قد تم تحديدها وتخزينها أصلاً كعدد صحيح (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | يحدد ما إذا كانت القيمة العددية لهذا الطول عددًا سالبًا. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | يحدد ما إذا كانت القيمة العددية لهذا الطول عددًا موجبًا. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | يحدد ما إذا كان الطول معطى بوحدات نسبية. لا يمكن تحويل مثل هذا الطول إلى بكسلات. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | القيمة من نوع بدون وحدة، لكنها ليست صفرًا - إنها عدد موجب أو سالب. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | يحدد ما إذا كان هذا الكائن صفرًا بدون وحدة أم لا. الصفر بدون وحدة هو القيمة الافتراضية لهذا النوع. نفس خاصية IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | يحدد ما إذا كانت القيمة العددية لهذا الطول عددًا صفرًا. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | يرجع نوع الوحدة لهذا الكائن Length. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | ينشئ ويرجع كائنًا من نوع Length باستخدام عدد مزدوج محدد ووحدة. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | ينشئ ويرجع كائنًا من نوع Length باستخدام عدد عائم محدد ووحدة. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | ينشئ ويرجع كائنًا من نوع Length باستخدام عدد صحيح محدد ووحدة. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | يقوم بتحليل وإرجاع السلسلة المحددة كقيمة Length، بما في ذلك قيمتها العددية واسم الوحدة، أو يرمي استثناءً عند الفشل. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | يرجع نسخة كاملة من هذا الكائن Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | يحدد ما إذا كانت هذه القيمة مساوية للطول المحدد الآخر. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | يحدد ما إذا كان هذا الطول مساويًا للكائن المحدد. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | يحسب ويرجع رمز تجزئة (hash-code) لهذا الكائن Length من خلال دمج رموز التجزئة للقيمة ونوع الوحدة. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | يرجع تمثيلًا نصيًا لهذا الطول بصيغته الأصلية (كما هو مخزن)، دون تحويل قيمة الطول إلى نوع وحدة آخر. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | يحول الطول إلى الوحدة المعطاة إذا كان ذلك ممكنًا. إذا كانت الوحدة الحالية أو المعطاة نسبية، سيتم رمي استثناء. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | يحول الطول إلى عدد من البكسلات إذا كان ذلك ممكنًا. إذا كانت الوحدة الحالية نسبية، سيتم رمي استثناء. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | يعيد تمثيلًا نصيًا لهذا الطول بنوع الوحدة المحدد. سيتم تحويل القيمة الرقمية وفقًا لتغيير نوع الوحدة. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | يحاول تحليل اسم الوحدة المحدد وإرجاع القيمة المقابلة لتعداد Unit. يُعيد Unit.Unitless إذا تعذر العثور على وحدة مناسبة. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | يحاول تحليل سلسلة محددة كقيمة Length، بما في ذلك قيمتها الرقمية واسم الوحدة |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | يفحص مساواة الطولين المُعطَين. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | يفحص عدم مساواة الطولين المُعطَين. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | يضرب Length المعطى في العامل المحدد |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | صفر عدد صحيح بدون وحدة - القيمة الافتراضية، نفس قيمة المُنشئ الافتراضي بدون معلمات |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## الأعضاء الآخرون

| الاسم | الوصف |
| --- | --- |
| enum [Unit](length.unit) | جميع وحدات الطول المدعومة |

### ملاحظات

يغطي هذا النوع أنواع البيانات CSS التالية: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### انظر أيضًا

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
