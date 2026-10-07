---
title: "GetFirstDefined"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع أول نوع خط من المجموعة المحددة الذي ليس قيمة Undefined أو نوع خط Undefined، وإلا يرجع نوع خط Undefined عندما تكون جميع العناصر Undefined"
type: docs
weight: 80
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined/
---
## FontType.GetFirstDefined method

يرجع أول نوع خط من المجموعة المحددة لا يكون قيمة "Undefined"، أو نوع الخط "Undefined" إذا كانت جميع العناصر "Undefined"

```csharp
public static FontType GetFirstDefined(params FontType[] fonts)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الخطوط | FontType[] | قيمة أو أكثر من FontType، NULL أو مجموعة فارغة غير مسموح بها |

### قيمة الإرجاع

القيمة الأولى من FontType في المجموعة المحددة التي ليست Undefined، أو Undefined إذا كانت جميع العناصر Undefined

### انظر أيضًا

* struct [FontType](../../fonttype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
