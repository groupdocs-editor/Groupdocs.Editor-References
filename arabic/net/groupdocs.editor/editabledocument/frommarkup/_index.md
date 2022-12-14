---
title: FromMarkup
second_title: GroupDocs.Editor لمرجع .NET API
description: مصنع ثابت  يقوم بإنشاء مثيل EditableDocument من ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة
type: docs
weight: 20
url: /ar/net/groupdocs.editor/editabledocument/frommarkup/
---
## EditableDocument.FromMarkup method

مصنع ثابت ، يقوم بإنشاء مثيل EditableDocument من ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newHtmlContent | String | سلسلة ، تحتوي على ترميز HTML خام ، يجب تحليله. لا يمكن أن يكون فارغًا أو فارغًا أو غير صالح. |
| resources | IEnumerable`1 | مجموعة من جميع الموارد (الصور ، أوراق الأنماط ، الخطوط) ، التي يتم استخدامها في مستند HTML ، المحدد في*newHtmlContent* معامل. قد تكون غائبة (مجموعة فارغة أو فارغة). |

### قيمة الإرجاع

مثيل جديد غير فارغ لـ EditableDocument

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | لا يمكن أن تكون السلسلة التي تحتوي على ترميز HTML خام للإدخال فارغة أو فارغة |

### أنظر أيضا

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* مساحة الاسم [GroupDocs.Editor](../../editabledocument)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
