---
title: "صالح"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحقق مما إذا كان التدفق المحدد خط TTF صالحًا"
type: docs
weight: 40
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/isvalid/
---
## IsValid(Stream) {#isvalid}

يتحقق مما إذا كان التدفق المحدد خط TTF صالحًا

```csharp
public static bool IsValid(Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى الثنائي | Stream | تدفق بايت يُفترض أنه يحتوي على مورد TTF |

### قيمة الإرجاع

صحيح إذا كان التدفق المحدد يحتوي على خط TTF صالح، وإلا خاطئ

### انظر أيضًا

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة خط TTF صالحًا

```csharp
public static bool IsValid(string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contentInBase64 | String | محتوى الخط TTF المفترض على شكل سلسلة مشفرة بقاعدة64 |

### قيمة الإرجاع

صحيح إذا كانت السلسلة المحددة تحتوي على خط TTF صالح، وإلا خاطئ

### انظر أيضًا

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
