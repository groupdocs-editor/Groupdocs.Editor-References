---
title: "SvgImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ مثيلًا جديدًا من SvgImage من محتوى ممثل كسلسلة عادية ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

ينشئ كائن SvgImage جديد من المحتوى، الممثل كسلسلة نصية عادية، ومع اسم محدد

```csharp
public SvgImage(string name, string content)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة SVG. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| المحتوى | String | المحتوى كسلسلة عادية، يحتوي على محتوى صالح ومتوافق مع XML لصورة SVG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى SVG، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | بعض المعلمات غير صالحة |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* يحتوي على محتوى SVG غير صالح |

### انظر أيضًا

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

ينشئ كائن SvgImage جديد من المحتوى، الممثل كتيار بايت، ومع اسم محدد

```csharp
public SvgImage(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة SVG. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
