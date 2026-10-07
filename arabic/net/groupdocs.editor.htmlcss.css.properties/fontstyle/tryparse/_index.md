---
title: "TryParse"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة للخط FontStyle وإرجاعها عند النجاح أو NULL عند الفشل."
type: docs
weight: 80
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse/
---
## FontStyle.TryParse method

يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة لـ 'font-style' وإرجاعها عند النجاح أو NULL عند الفشل.

```csharp
public static bool TryParse(string keyword, out FontStyle result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة مفتاحية | String | كلمة مفتاحية للتحليل |
| result | FontStyle& | النتيجة، إذا كان التحليل ناجحًا، أو [`Normal`](../normal) وإلا |

### قيمة الإرجاع

true إذا كان التحليل ناجحًا، false وإلا

### انظر أيضًا

* struct [FontStyle](../../fontstyle)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
