---
title: "WoffFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة WoffFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

ينشئ فئة WoffFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64، وبالاسم المحدد

```csharp
public WoffFont(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. إذا لم يكن محتوى WOFF، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

ينشئ فئة WoffFont جديدة من المحتوى الممثل كتيار بايت، وبالاسم المحدد

```csharp
public WoffFont(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والبحث. إذا تم التخلص من هذه الحالة، سيتم أيضًا التخلص من هذا التيار. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
