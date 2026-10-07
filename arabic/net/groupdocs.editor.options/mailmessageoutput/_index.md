---
title: "MailMessageOutput"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحكم في الأجزاء التي يجب أن يتم تسليمها من رسالة البريد إلى المعالجة الناتجة."
type: docs
weight: 960
url: /ar/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

يتحكم في الأجزاء التي يجب أن يتم تسليمها من رسالة البريد إلى المعالجة الناتجة.

```csharp
[Flags]
public enum MailMessageOutput
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لن يتم معالجة أي من أجزاء رسالة البريد الإلكتروني |
| Body | `1` | معالجة محتوى رسالة البريد |
| Subject | `2` | معالجة موضوع رسالة البريد |
| Date | `4` | معالجة التاريخ والوقت عندما تم تسليم الرسالة |
| To | `8` | معالجة جميع مستلمي رسالة البريد |
| Cc | `10` | معالجة جميع مستلمي النسخة الكربونية (CC) لرسالة البريد |
| Bcc | `20` | معالجة جميع مستلمي النسخة المخفية (BCC) لرسالة البريد |
| From | `40` | معالجة مرسل رسالة البريد |
| Attachments | `80` | معالجة جميع مرفقات رسالة البريد |
| Metadata | `100` | معالجة جميع البيانات الوصفية التقنية الأخرى (الحساسية، الأولوية، الترميز، MIME، X-Mailer، إلخ) |
| Common | `7B` | الإخراج الشائع - الجسم مع جميع البيانات الوصفية الرئيسية |
| All | `1FF` | الإخراج الكامل - الجسم مع جميع البيانات الوصفية |

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
