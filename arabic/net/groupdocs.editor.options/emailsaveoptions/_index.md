---
title: "EmailSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات البريد الإلكتروني."
type: docs
weight: 860
url: /ar/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات البريد الإلكتروني

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | ينشئ مثيلاً جديداً من الفئة [`EmailSaveOptions`](../emailsaveoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية. |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | ينشئ مثيلاً جديداً من الفئة [`EmailSaveOptions`](../emailsaveoptions) مع معامل [`MailMessageOutput`](./mailmessageoutput). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مستند البريد الإلكتروني الناتج، الذي سيتم إنشاؤه وحفظه باستخدام طريقة [`Save`](../../groupdocs.editor/editor/save). |

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
