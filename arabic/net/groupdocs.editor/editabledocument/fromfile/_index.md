---
title: "FromFile"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "مصنع ثابت ينشئ مثيلًا من EditableDocument من ملف HTML يُحدَّد بمسار ملف .html نفسه ومجلد يحتوي على الموارد المرتبطة"
type: docs
weight: 10
url: /ar/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

مصنع ثابت، ينشئ كائنًا من EditableDocument من ملف HTML، يتم تحديده عبر مسار ملف *.html نفسه ومجلد يحتوي على الموارد المرتبطة

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlFilePath | String | سلسلة، تحتوي على مسار كامل لملف HTML. لا يمكن أن تكون null، يجب أن يكون مسار ملف صالح، ويجب أن يكون الملف نفسه موجودًا. |
| resourceFolderPath | String | مسار اختياري للمجلد الذي يحتوي على موارد HTML. إذا كان NULL أو غير صالح أو لم يكن المجلد موجودًا، سيحاول المحرر العثور على هذا المجلد بنفسه من خلال تحليل علامات HTML |

### قيمة الإرجاع

مثيل جديد غير فارغ من EditableDocument

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | مسار ملف HTML و/أو مسار مجلد الموارد غير صالح |
| FileNotFoundException | ملف HTML المحدد لا يمكن العثور عليه |

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
