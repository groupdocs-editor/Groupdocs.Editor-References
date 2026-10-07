---
title: "EmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ كائن EmfImage جديد من المحتوى الممثل كسلسلة base64 ومُعطى الاسم المحدد."
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/emfimage/
---
## EmfImage(string, string) {#constructor_1}

ينشئ نسخة جديدة من EmfImage من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وبالاسم المحدد

```csharp
public EmfImage(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة EMF. لا يمكن أن يكون NULL أو فارغًا أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة base64. لا يمكن أن تكون NULL أو فارغة أو تحتوي على مسافات فقط. إذا لم يكن محتوى EMF، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## EmfImage(string, Stream) {#constructor}

ينشئ نسخة جديدة من EmfImage من المحتوى الممثل كتدفق بايت، وبالاسم المحدد

```csharp
public EmfImage(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم صورة EMF. لا يمكن أن يكون NULL أو فارغًا أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### انظر أيضًا

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
