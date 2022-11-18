---
title: FromFile
second_title: GroupDocs.Editor لمرجع .NET API
description: مصنع ثابت  يقوم بإنشاء مثيل EditableDocument من ملف HTML  المحدد بواسطة مسار إلى ملف  .html نفسه ومجلد به موارد مرتبطة
type: docs
weight: 10
url: /ar/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

مصنع ثابت ، يقوم بإنشاء مثيل EditableDocument من ملف HTML ، المحدد بواسطة مسار إلى ملف * .html نفسه ومجلد به موارد مرتبطة

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| htmlFilePath | String | سلسلة ، تحتوي على مسار كامل لملف HTML. لا يمكن أن تكون خالية ، يجب أن تكون مسار ملف صالحًا ، ويجب أن يكون الملف نفسه موجودًا. |
| resourceFolderPath | String | مسار اختياري للمجلد الذي يحتوي على موارد HTML . إذا كان المجلد NULL أو غير صالح أو لم يكن هذا المجلد موجودًا ، فسيحاول المحرر العثور على هذا المجلد بنفسه ، وتحليل ترميز HTML |

### قيمة الإرجاع

مثيل جديد غير فارغ لـ EditableDocument

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | مسار ملف HTML و / أو مسار مجلد المورد غير صالح |
| FileNotFoundException | لا يمكن العثور على ملف HTML المحدد |

### أنظر أيضا

* class [EditableDocument](../../editabledocument)
* مساحة الاسم [GroupDocs.Editor](../../editabledocument)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->