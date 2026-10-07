---
title: "TtfFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة TtfFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

ينشئ فئة TtfFont جديدة من المحتوى، الممثل كسلسلة مشفرة بقاعدة64، ومع اسم محدد

```csharp
public TtfFont(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط TTF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى TTF، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

ينشئ فئة TtfFont جديدة من المحتوى، الممثل كتدفق بايت، ومع اسم محدد

```csharp
public TtfFont(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط TTF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | يتم رمي الاستثناء عندما لا يمكن تفسير المحتوى الثنائي المحدد بشكل صحيح كخط TTF صالح |

### انظر أيضًا

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
