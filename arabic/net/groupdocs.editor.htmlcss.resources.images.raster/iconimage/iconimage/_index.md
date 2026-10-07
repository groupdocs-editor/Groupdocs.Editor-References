---
title: "IconImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ مثيلة جديدة من IconImage من المحتوى الممثل كسلسلة base64encoded ومع الاسم المحدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/iconimage/
---
## IconImage(string, string) {#constructor_1}

ينشئ نسخة جديدة من IconImage من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وبالاسم المحدد

```csharp
public IconImage(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة ICON. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة base64-encoded. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى ICON، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IconImage(string, Stream) {#constructor}

ينشئ نسخة جديدة من IconImage من المحتوى الممثل كتيار بايت، وبالاسم المحدد

```csharp
public IconImage(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة ICON. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
