---
title: "FromMarkup"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "مصنع ثابت ينشئ مثيلًا من EditableDocumentgroupdocs.editor/editabledocument من ترميز HTML المحدد"
type: docs
weight: 20
url: /ar/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

مصنع ثابت، ينشئ مثيلًا من [`EditableDocument`](../../editabledocument) من ترميز HTML المحدد

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newHtmlContent | String | سلسلة تحتوي على علامة HTML خام يجب تحليلها. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |

### قيمة الإرجاع

مثيل جديد غير فارغ من EditableDocument

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | السلسلة التي تحتوي على ترميز HTML الخام المدخل لا يمكن أن تكون فارغة أو NULL |

### ملاحظات

هذه الطريقة الثابتة مفيدة لإنشاء مثيل [`EditableDocument`](../../editabledocument) من ترميز HTML المكوّن من سلسلة واحدة، حيث يتم تضمين جميع الموارد فيه باستخدام ترميز base64.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

مصنع ثابت، ينشئ كائنًا من EditableDocument من ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newHtmlContent | String | سلسلة تحتوي على علامة HTML خام يجب تحليلها. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
| resources | IEnumerable`1 | مجموعة جميع الموارد (الصور، أوراق الأنماط، الخطوط) التي تُستخدم في مستند HTML، المحددة في معامل *newHtmlContent*. قد تكون غير موجودة (NULL أو مجموعة فارغة). |

### قيمة الإرجاع

مثيل جديد غير فارغ من EditableDocument

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | السلسلة التي تحتوي على ترميز HTML الخام المدخل لا يمكن أن تكون فارغة أو NULL |

### انظر أيضًا

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
