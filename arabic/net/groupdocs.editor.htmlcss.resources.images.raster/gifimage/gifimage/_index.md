---
title: "GifImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ كائن GifImage جديد من المحتوى الممثل كسلسلة مشفرة بقاعدة 64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/gifimage/
---
## GifImage(string, string) {#constructor_1}

ينشئ كائن GifImage جديد من المحتوى، الممثل كنص مشفر بـ base64، ومع اسم محدد

```csharp
public GifImage(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة GIF. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى GIF، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## GifImage(string, Stream) {#constructor}

ينشئ كائن GifImage جديد من المحتوى، الممثل كدفق بايت، ومع اسم محدد

```csharp
public GifImage(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة GIF. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
