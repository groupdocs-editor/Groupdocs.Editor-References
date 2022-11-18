---
title: MailMessageOutput
second_title: GroupDocs.Editor لمرجع .NET API
description: يتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى معالجة الإخراج
type: docs
weight: 790
url: /ar/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

يتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى معالجة الإخراج

```csharp
[Flags]
public enum MailMessageOutput : ushort
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| None | `0` | لن تتم معالجة أي جزء من أجزاء رسالة البريد الإلكتروني |
| Body | `1` | نص العملية لرسالة البريد |
| Subject | `2` | موضوع العملية لرسالة البريد |
| Date | `4` | تاريخ ووقت العملية عند تسليم الرسالة |
| To | `8` | معالجة كافة مستلمي رسالة البريد |
| Cc | `10` | معالجة كافة مستلمي CC لرسالة البريد |
| Bcc | `20` | معالجة كافة مستلمي BCC لرسالة البريد |
| From | `40` | معالجة مرسل رسالة البريد |
| Attachments | `80` | معالجة كافة مرفقات رسالة البريد |
| Metadata | `100` | معالجة جميع البيانات الوصفية التقنية الأخرى (الحساسية ، والأولوية ، والتشفير ، و MIME ، و X-Mailer ، وما إلى ذلك) |
| Common | `7B` | إخراج عام - نص مع جميع البيانات الوصفية الرئيسية |
| All | `1FF` | إخراج كامل - نص مع جميع البيانات الوصفية |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->