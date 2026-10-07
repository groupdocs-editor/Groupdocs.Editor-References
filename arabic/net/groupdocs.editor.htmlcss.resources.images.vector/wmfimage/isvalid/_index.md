---
title: "صالح"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحقق مما إذا كان التدفق المحدد صورة WMF صالحة"
type: docs
weight: 90
url: /ar/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

يتحقق مما إذا كان التدفق المحدد صورة WMF صالحة

```csharp
public static bool IsValid(Stream binaryContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى الثنائي | Stream | تدفق بايت إدخال. لا يمكن أن يكون NULL، يجب أن يدعم القراءة والبحث. |

### قيمة الإرجاع

صحيح إذا كان التدفق المحدد يحتوي على صورة WMF صالحة، وإلا خطأ

### انظر أيضًا

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة صورة WMF صالحة

```csharp
public static bool IsValid(string contentInBase64)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contentInBase64 | String | سلسلة الإدخال، حيث يتم تخزين محتوى صورة WMF بترميز base64. لا يمكن أن تكون NULL أو فارغة. |

### قيمة الإرجاع

صحيح إذا كانت السلسلة المحددة تحتوي على صورة WMF صالحة، وإلا خاطئ.

### انظر أيضًا

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
