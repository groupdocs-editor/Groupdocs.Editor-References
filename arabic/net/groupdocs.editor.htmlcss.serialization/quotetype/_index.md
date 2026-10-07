---
title: "QuoteType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل أحرف الاقتباس  الاقتباس المفرد  والاقتباس المزدوج"
type: docs
weight: 660
url: /ar/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

يمثل أحرف الاقتباس - الفاصلة المفردة (') والفاصلة المزدوجة (")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | الحرف لتغليفه |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | نقطة الشيفرة للحرف الحالي (U+0027 أو U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | حرف مُشفّر بـ HTML |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | يشير إلى ما إذا كانت هذه النسخة من نوع الاقتباس مساوية للمعطى غير محوّل |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | يشير إلى ما إذا كانت هذه النسخة من نوع الاقتباس مساوية للمعطى المحدد |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | يرجع قيمة تجزئة (hash-code) لهذا الحرف |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | يرجع سلسلة "SingleQuote" أو "DoubleQuote" حسب القيمة الحالية |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | يتحقق مما إذا كانت قيمتي "QuoteType" متساويتين |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | يحوّل النسخة المحددة من [`QuoteType`](../quotetype) إلى الحرف (Char) (عاملان) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | يتحقق مما إذا كانت قيمتين من "QuoteType" غير متساويتين |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | علامة اقتباس مزدوجة (U+0022 حرف علامة الاقتباس) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | علامة اقتباس مفردة (U+0027 حرف الفاصلة العليا) |

### انظر أيضًا

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
