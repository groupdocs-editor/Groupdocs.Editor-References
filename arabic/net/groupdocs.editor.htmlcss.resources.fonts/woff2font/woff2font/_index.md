---
title: "Woff2Font"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة Woff2Font جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

ينشئ فئة Woff2Font جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وباسم محدد

```csharp
public Woff2Font(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى WOFF2، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

ينشئ فئة Woff2Font جديدة من المحتوى الممثل كتيار بايت، وباسم محدد

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والبحث. إذا تم التخلص من هذه الحالة، سيتم أيضًا التخلص من هذا التيار. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
