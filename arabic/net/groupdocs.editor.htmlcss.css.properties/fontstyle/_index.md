---
title: "FontStyle"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحدد كيفية تنسيق الخط بنمط عادي أو مائل أو مائل من عائلة الخط الخاصة به."
type: docs
weight: 270
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

يحدد كيفية تنسيق الخط: عادي، مائل، أو مائل مائل من عائلة الخط.

```csharp
public struct FontStyle
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | يشير إلى ما إذا كان نمط الخط هذا له قيمة مبدئية (عادي) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | يعيد قيمة نمط الخط هذا كسلسلة نصية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | يحدد ما إذا كانت نسخة نمط الخط هذه مساوية للمحددة |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | يحدد ما إذا كانت نسخة نمط الخط هذه مساوية للمحددة غير المحوّلة |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | يعيد رمز تجزئة (hash-code) لهذه النسخة |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة لـ 'font-style' وإرجاعها عند النجاح أو NULL عند الفشل. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | يتحقق مما إذا كانت قيمتي "FontStyle" متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | يتحقق مما إذا كانت قيمتي "FontStyle" غير متساويتين |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | يختار خطًا مصنفًا كـ مائل. إذا لم يتوفر إصدار مائل من الخط، يُستخدم إصدار مصنف كمنحني بدلاً من ذلك. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | يختار خطًا مصنفًا كعادي داخل عائلة الخطوط. القيمة الأولية. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | يختار خطًا مصنفًا كمنحني. إذا لم يتوفر إصدار منحني من الخط، يُستخدم إصدار مصنف كـ مائل بدلاً من ذلك. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا. |

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
