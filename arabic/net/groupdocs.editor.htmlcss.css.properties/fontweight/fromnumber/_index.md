---
title: FromNumber
second_title: GroupDocs.Editor لمرجع .NET API
description: إنشاء وزن خط من رقم محدد
type: docs
weight: 50
url: /ar/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

إنشاء وزن خط من رقم محدد

```csharp
public static FontWeight FromNumber(ushort number)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | UInt16 | عدد صحيح بدون إشارة ، يجب أن يكون ضمن النطاق [1..1000] |

### قيمة الإرجاع

مثيل FontWeight جديد أو استثناء

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | الرقم المحدد خارج النطاق [1..1000] |

### أنظر أيضا

* struct [FontWeight](../../fontweight)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Css.Properties](../../fontweight)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
