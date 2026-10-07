---
title: "TextDecorationLineType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل أنواع خط الزينة النصية: تحت الخط، الشرطة السفلية، فوق الخط، وخط الشطب"
type: docs
weight: 290
url: /ar/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

يمثل أنواع خط تزيين النص: تسطير (underscore)، خط فوق (overline)، وخط شطب (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | يشير إلى ما إذا كانت هذه الحالة لها قيمة أولية — لا شيء |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | يشير إلى ما إذا كان خط الشطب (line-through) مفعلاً |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | يشير إلى ما إذا كان فوق الخط مفعلاً |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | يشير إلى ما إذا كان تحت الخط (الشرطة السفلية) مفعلاً |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | يعيد قيمة جميع العلامات في هذه الحالة كنص |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | ينشئ ويعيد حالة [`TextDecorationLineType`](../textdecorationlinetype) مع العلامات المحددة بواسطة المعلمات المحددة |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | يشير إلى ما إذا كان هذا الكائن [`TextDecorationLineType`](../textdecorationlinetype) مساويًا للمعطى غير المحول |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | يشير إلى ما إذا كان هذا الكائن [`TextDecorationLineType`](../textdecorationlinetype) مساويًا للمعطى |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | يرجع رمز تجزئة (hash-code) لهذا الكائن |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | يعيد قيمة جميع العلامات في هذه الحالة كنص |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | يحاول تحليل سلسلة محددة وإرجاع كائن [`TextDecorationLineType`](../textdecorationlinetype) صالح |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | يجمع (يدمج) نوعين محددين من الخطوط وينتج نوع خط جديد نتيجةً، حيث يتم دمج العلامات (الاتحاد) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | يرجع تقاطعًا بين النوع الأول والنوع الثاني من الخطوط، حيث يتم تمكين العلامات التي تم تمكينها في الوقت نفسه في كلا العاملين فقط. له أعلى أولوية بين جميع العمليات (أعلى من الاتحاد والفرق) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | يفحص ما إذا كانت قيمتي "TextDecorationLineType" متساويتين |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | يحوّل البايت المحدد (ثمانية بتات) إلى [`TextDecorationLineType`](../textdecorationlinetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح (عاملان) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | يفحص ما إذا كانت قيمتي "TextDecorationLineType" غير متساويتين |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | يطرح نوع الخط المحدد الثاني من نوع الخط المحدد الأول وينتج نوع خط جديد نتيجةً، حيث توجد فقط العلامات من العامل الأول التي لا توجد في العامل الثاني (الفرق) |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | كل سطر نص له خط يمر عبر الوسط. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | ينتج بدون أي زخرفة نصية. القيمة الأولية. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | كل سطر نص له خط فوقه. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | كل سطر نص مُسطّر. |

### ملاحظات

هيكل غير قابل للتغيير. مشابه لـ https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
