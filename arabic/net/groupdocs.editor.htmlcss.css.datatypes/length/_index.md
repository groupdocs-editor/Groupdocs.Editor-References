---
title: Length
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل قيمة طول CSS في أي وحدة يمكن دعمها  بما في ذلك النسبة المئوية والنوع بدون وحدة . قد تكون القيم عددًا صحيحًا أو عددًا عائمًا  وسالب وصفر وموجب. هيكل ثابت.
type: docs
weight: 260
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

يمثل قيمة طول CSS في أي وحدة يمكن دعمها ، بما في ذلك النسبة المئوية والنوع بدون وحدة . قد تكون القيم عددًا صحيحًا أو عددًا عائمًا ، وسالب وصفر وموجب. هيكل ثابت.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | إرجاع قيمة رقمية عائمة لمثيل الطول. لا يطرح استثناءً مطلقًا - يحول قيمة عدد صحيح إلى عائم إذا لزم الأمر. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | تُرجع قيمة عددية صحيحة لمثيل الطول هذا ، إذا تم تخزينه داخليًا كعدد صحيح ، أو يطرح استثناءً ، إذا تم تخزينه في الأصل كرقم عائم. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | تحصل عليه إذا تم إعطاء الطول بالوحدات المطلقة. يمكن تحويل هذا الطول إلى بكسل. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | يشير إلى ما إذا كانت القيمة الرقمية لمثيل الطول هذا قد تم تحديدها وتخزينها في الأصل كرقم عائم (FP32 ) |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | يشير إلى ما إذا كانت القيمة الرقمية لمثيل الطول هذا قد تم تحديدها وتخزينها في الأصل كعدد صحيح (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | لتحديد ما إذا كانت القيمة الرقمية لهذا الطول رقمًا سلبيًا |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | تحديد ما إذا كانت القيمة الرقمية لهذا الطول رقمًا موجبًا |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | تحصل عليه إذا تم إعطاء الطول بالوحدات النسبية. لا يمكن تحويل هذا الطول إلى بكسل. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | تحتوي القيمة على نوع بدون وحدة ، ولكنها ليست صفراً - رقم موجب أو سالب |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | لتحديد ما إذا كان هذا المثيل عبارة عن صفر بدون وحدة أم لا. الصفر اللامحدود هو القيمة الافتراضية لهذا النوع. نفس الخاصية الافتراضية. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | لتحديد ما إذا كانت القيمة الرقمية لهذا الطول هي رقم صفري |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | إرجاع نوع الوحدة لمثيل الطول هذا. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | إنشاء وإرجاع مثيل من نوع الطول بواسطة رقم مزدوج محدد و unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | إنشاء وإرجاع مثيل من نوع الطول بواسطة رقم عائم محدد و unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | إنشاء وإرجاع مثيل من نوع الطول بواسطة رقم صحيح محدد و unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | يوزع ويعيد السلسلة المحددة كقيمة طول ، بما في ذلك القيمة الرقمية واسم الوحدة ، أو يطرح استثناءً على failure |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | إرجاع نسخة كاملة من مثيل الطول هذا |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | يحدد ما إذا كانت هذه القيمة تساوي الطول المحدد الآخر |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | تحديد ما إذا كان هذا الطول يساوي object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | حساب وإرجاع رمز تجزئة لمثيل الطول هذا من خلال دمج رموز التجزئة للقيمة ونوع الوحدة |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | إرجاع تمثيل سلسلة لهذا الطول في شكله الأصلي الأصلي (كما هو مخزّن) ، بدون تحويل قيمة الطول إلى نوع وحدة أخرى من النوع |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | تحويل الطول إلى وحدة معينة ، إن أمكن. إذا كانت الوحدة الحالية أو الحالية نسبيًا ، فسيتم طرح استثناء. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | تحويل الطول إلى عدد من البكسل ، إن أمكن. إذا كانت الوحدة الحالية نسبية ، فسيتم طرح استثناء. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | إرجاع تمثيل سلسلة بهذا الطول في نوع وحدة محدد. سيتم تحويل القيمة الرقمية المقابلة لتغيير نوع الوحدة. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | يحاول تحليل اسم الوحدة المحدد وإرجاع القيمة المقابلة لتعداد الوحدة. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | يحاول تحليل سلسلة محددة كقيمة طول ، بما في ذلك قيمتها الرقمية واسم الوحدة |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | للتحقق من المساواة بين الطولين المحددين. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | للتحقق من عدم المساواة بين الطولين المحددين. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | يضاعف الطول المحدد في العامل المحدد |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50٪ |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100٪ |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | عدد صحيح بدون وحدة صفر - القيمة الافتراضية ، نفس المُنشئ الافتراضي بدون معلمات |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0٪ |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| enum [Unit](length.unit) | جميع وحدات الطول المدعومة |

### ملاحظات

يغطي هذا النوع أنواع بيانات CSS التالية: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS / النسبة المئوية

### أنظر أيضا

* interface [ICssDataType](../icssdatatype)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
