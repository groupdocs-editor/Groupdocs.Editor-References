---
title: "TtcFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ فئة TtcFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64 ومع اسم محدد"
type: docs
weight: 10
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

ينشئ فئة TtcFont جديدة من المحتوى الممثَّل كنص مشفر بقاعدة 64، ومع اسم محدد

```csharp
public TtcFont(string name, string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط TTC. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| contentInBase64 | String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى TTC، سيتم رمي استثناء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | أي من سلاسل الإدخال هي `null` أو فارغة أو تحتوي على مسافات فقط |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | المحتوى في معامل *contentInBase64* لا يمكن التعرف عليه كخط TTC صالح |

### انظر أيضًا

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

ينشئ فئة TtcFont جديدة من المحتوى الممثَّل كتيار بايت، ومع اسم محدد

```csharp
public TtcFont(string name, Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | اسم خط TTC. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
| المحتوى الثنائي | Stream | المحتوى كدفق بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون NULL. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذا الكائن، سيتم تحرير هذا الدفق أيضًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | معامل *name* هو `null` أو فارغ أو يحتوي على مسافات فقط |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | يتم رمي الاستثناء عندما لا يمكن تفسير المحتوى الثنائي المحدد بشكل صحيح كخط TTF صالح |

### انظر أيضًا

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
