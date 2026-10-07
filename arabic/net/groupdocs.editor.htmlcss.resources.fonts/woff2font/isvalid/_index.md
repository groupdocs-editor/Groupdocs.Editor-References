---
title: "صالح"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحقق مما إذا كان التيار المحدد خط WOFF2 صالحًا"
type: docs
weight: 40
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid/
---
## IsValid(Stream) {#isvalid}

يتحقق مما إذا كان التيار المحدد خط WOFF2 صالحًا

```csharp
public static bool IsValid(Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى الثنائي | Stream | تدفق بايت يُفترض أنه يحتوي على مورد WOFF2 |

### قيمة الإرجاع

صحيح إذا كان التدفق المحدد يحتوي على خط WOFF2 صالح، وإلا خاطئ

### انظر أيضًا

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة خط WOFF2 صالحًا

```csharp
public static bool IsValid(string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contentInBase64 | String | محتوى الخط المفترض أنه WOFF2 على شكل سلسلة مشفرة بقاعدة64 |

### قيمة الإرجاع

صحيح إذا كانت السلسلة المحددة تحتوي على خط WOFF2 صالح، وإلا خاطئ

### انظر أيضًا

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
