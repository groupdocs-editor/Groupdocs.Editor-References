---
title: "TryParse"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحاول تحليل سلسلة محددة كقيمة Length بما في ذلك قيمتها الرقمية واسم الوحدة."
type: docs
weight: 280
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/length/tryparse/
---
## Length.TryParse method

يحاول تحليل سلسلة محددة كقيمة Length، بما في ذلك قيمتها الرقمية واسم الوحدة

```csharp
public static bool TryParse(string input, out Length result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الإدخال | String | السلسلة المدخلة التي يجب تحليلها |
| النتيجة | Length& | معامل الإخراج، الذي يحتوي على نتيجة التحليل. إذا فشل التحليل، يحتوي على قيمة Length افتراضية — صفر بلا وحدة. |

### قيمة الإرجاع

صحيح إذا كان التحليل ناجحًا، خطأ إذا فشل.

### انظر أيضًا

* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
