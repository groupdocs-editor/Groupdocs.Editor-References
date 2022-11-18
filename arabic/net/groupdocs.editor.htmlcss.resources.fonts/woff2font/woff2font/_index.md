---
title: Woff2Font
second_title: GroupDocs.Editor لمرجع .NET API
description: إنشاء فئة Woff2Font جديدة من المحتوى  يتم تمثيلها كسلسلة مشفرة بـ base64  وباسم محدد
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

إنشاء فئة Woff2Font جديدة من المحتوى ، يتم تمثيلها كسلسلة مشفرة بـ base64 ، وباسم محدد

```csharp
public Woff2Font(string name, string contentInBase64)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| contentInBase64 | String | المحتوى كسلسلة بترميز base64. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. إذا لم يكن محتوى WOFF2 ، فسيتم طرح استثناء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### أنظر أيضا

* class [Woff2Font](../../woff2font)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../woff2font)
* المجسم [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

إنشاء فئة Woff2Font جديدة من المحتوى ، يتم تمثيلها على شكل دفق بايت ، وباسم محدد

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو فارغًا أو مسافات بيضاء. |
| binaryContent | Stream | المحتوى كتيار بايت. تبدأ القراءة من الموضع الأصلي. لا يمكن أن تكون لاغية. يجب أن يكون مقروءًا وقابلًا للنطق. إذا تم التخلص من هذا المثيل ، فسيتم التخلص من هذا التدفق أيضًا. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### أنظر أيضا

* class [Woff2Font](../../woff2font)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../woff2font)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->