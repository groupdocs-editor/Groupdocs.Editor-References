---
title: "صالح"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحقق مما إذا كان التدفق المحدد خط EOT صالحًا"
type: docs
weight: 40
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid/
---
## IsValid(Stream) {#isvalid}

يتحقق مما إذا كان التدفق المحدد خط EOT صالحًا

```csharp
public static bool IsValid(Stream eotBinaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eotBinaryContent | Stream | تدفق بايت يُفترض أنه يحتوي على مورد EOT |

### قيمة الإرجاع

صحيح إذا كان التدفق المحدد يحتوي على خط EOT صالح، وإلا خاطئ

### انظر أيضًا

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خطًا صالحًا من نوع EOT

```csharp
public static bool IsValid(string eotContentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eotContentInBase64 | String | محتوى الخط EOT المفترض على شكل سلسلة مشفرة بقاعدة 64 |

### قيمة الإرجاع

صحيح إذا كانت السلسلة المحددة تحتوي على خط EOT صالح، وإلا خاطئ

### انظر أيضًا

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
