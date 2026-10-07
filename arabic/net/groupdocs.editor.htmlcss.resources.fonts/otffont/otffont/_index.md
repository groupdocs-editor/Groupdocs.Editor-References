---
title: "OtfFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة OtfFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

ينشئ فئة OtfFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64، وبالاسم المحدد

```csharp
public OtfFont(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط OTF. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. إذا لم يكن محتوى OTF، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

ينشئ فئة OtfFont جديدة من المحتوى الممثل كتيار بايت، وبالاسم المحدد

```csharp
public OtfFont(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط OTF. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
