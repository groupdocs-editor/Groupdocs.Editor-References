---
title: "ToStringSpecified"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يعيد تمثيلًا نصيًا لهذا الطول بنوع الوحدة المحدد. سيتم تحويل القيمة الرقمية وفقًا لتغيير نوع الوحدة."
type: docs
weight: 260
url: /ar/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

يعيد تمثيلًا نصيًا لهذا الطول بنوع الوحدة المحدد. سيتم تحويل القيمة الرقمية وفقًا لتغيير نوع الوحدة.

```csharp
public string ToStringSpecified(Unit unit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| unit | Unit | الوحدة المحددة، التي يجب تحويل هذه المثيلة إليها قبل تسلسلها إلى السلسلة. يجب أن تكون صالحة. لا يمكن أن تكون بلا وحدة. |

### قيمة الإرجاع

تمثيل السلسلة

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidEnumArgumentException | القيمة غير معرفة |
| ArgumentOutOfRangeException | القيمة بلا وحدة محظورة |

### انظر أيضًا

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
