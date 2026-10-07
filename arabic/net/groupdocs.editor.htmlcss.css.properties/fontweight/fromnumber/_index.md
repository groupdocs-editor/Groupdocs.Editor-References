---
title: "FromNumber"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ fontweight من رقم محدد"
type: docs
weight: 50
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

ينشئ font-weight من رقم محدد

```csharp
public static FontWeight FromNumber(ushort number)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| رقم | UInt16 | عدد صحيح غير موقع، يجب أن يكون ضمن النطاق [1..1000] |

### قيمة الإرجاع

مثيل FontWeight جديد أو استثناء

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | الرقم المحدد خارج النطاق [1..1000] |

### انظر أيضًا

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
