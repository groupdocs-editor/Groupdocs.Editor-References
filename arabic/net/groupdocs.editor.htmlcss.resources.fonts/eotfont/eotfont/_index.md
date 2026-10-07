---
title: "EotFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة EotFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

ينشئ فئة EotFont جديدة من المحتوى، الممثل كسلسلة مشفرة بقاعدة64، ومع اسم محدد

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eotName | String | اسم خط EOT. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| eotContentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى EOT، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

ينشئ فئة EotFont جديدة من المحتوى، الممثل كتدفق بايت، ومع اسم محدد

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eotName | String | اسم خط EOT. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| eotBinaryContent | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
