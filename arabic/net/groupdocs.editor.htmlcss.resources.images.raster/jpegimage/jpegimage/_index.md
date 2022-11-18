---
title: JpegImage
second_title: GroupDocs.Editor لمرجع .NET API
description: إنشاء مثيل JpegImage جديد من المحتوى  يتم تمثيله كسلسلة مشفرة باستخدام base64  وباسم محدد
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.raster/jpegimage/jpegimage/
---
## JpegImage(string, string) {#constructor_1}

إنشاء مثيل JpegImage جديد من المحتوى ، يتم تمثيله كسلسلة مشفرة باستخدام base64 ، وباسم محدد

```csharp
public JpegImage(string name, string contentInBase64)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم صورة JPEG. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| contentInBase64 | String | المحتوى كسلسلة بترميز base64. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء . إذا لم يكن محتوى JPEG ، فسيتم طرح استثناء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### أنظر أيضا

* class [JpegImage](../../jpegimage)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../jpegimage)
* المجسم [GroupDocs.Editor](../../../)

---

## JpegImage(string, Stream) {#constructor}

إنشاء نسخة JpegImage جديدة من المحتوى ، يتم تمثيلها على شكل دفق بايت ، وباسم محدد

```csharp
public JpegImage(string name, Stream binaryContent)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم صورة JPEG. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| binaryContent | Stream | المحتوى كتيار بايت. تبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلاً للقراءة ويمكن البحث عنه. إذا تم التخلص من هذا المثيل ، فسيتم التخلص من هذا التدفق أيضًا. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### أنظر أيضا

* class [JpegImage](../../jpegimage)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../jpegimage)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->