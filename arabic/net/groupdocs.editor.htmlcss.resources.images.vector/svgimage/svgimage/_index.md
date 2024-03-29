---
title: SvgImage
second_title: GroupDocs.Editor لمرجع .NET API
description: إنشاء مثيل SvgImage جديد من المحتوى  يتم تمثيله كسلسلة عادية  وباسم محدد
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

إنشاء مثيل SvgImage جديد من المحتوى ، يتم تمثيله كسلسلة عادية ، وباسم محدد

```csharp
public SvgImage(string name, string content)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم صورة SVG. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| content | String | المحتوى كسلسلة عادية ، والتي تحتوي على محتوى صالح متوافق مع XML لصورة SVG. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء . إذا لم يكن محتوى SVG ، فسيتم طرح استثناء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | بعض المعلمات غير صالحة |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* تحتوي الوسيطة على محتوى SVG غير صالح |

### أنظر أيضا

* class [SvgImage](../../svgimage)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* المجسم [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

إنشاء مثيل SvgImage جديد من المحتوى ، يتم تمثيله على شكل دفق بايت ، وباسم محدد

```csharp
public SvgImage(string name, Stream binaryContent)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم صورة SVG. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| binaryContent | Stream | المحتوى كتيار بايت. تبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلاً للقراءة ويمكن البحث عنه. إذا تم التخلص من هذا المثيل ، فسيتم التخلص من هذا التدفق أيضًا. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### أنظر أيضا

* class [SvgImage](../../svgimage)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
