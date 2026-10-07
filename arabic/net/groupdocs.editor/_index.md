---
title: "GroupDocs.Editor"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تقدم مساحة الأسماء GroupDocs.Editor فئات لتحرير المستندات باستخدام محررات WYSIWYG الطرفية من طرف ثالث دون الحاجة إلى أي تطبيقات إضافية."
type: docs
weight: 10
url: /ar/net/groupdocs.editor/
---
توفر مساحة الاسم GroupDocs.Editor فئات لتحرير المستندات باستخدام محررات WYSIWYG للواجهة الأمامية من طرف ثالث دون أي تطبيقات إضافية.

## الفئات

| فئة | الوصف |
| --- | --- |
| [EditableDocument](./editabledocument) | مستند وسيط يحتوي على المحتوى قبل وبعد التحرير |
| [Editor](./editor) | الفئة الرئيسية التي تُغلف أساليب التحويل. توفر فئة Editor أساليب لتحميل المستندات وتحريرها وحفظها بجميع الصيغ المدعومة. هي قابلة للتصرف، لذا استخدم توجيه 'using' أو حرّر مواردها يدويًا عبر استدعاء الطريقة 'Dispose()'. يتم تحميل المستند من خلال المُنشئات. تحرير المستند يتم عبر الطريقة 'Edit'، وحفظ المستند الناتج بعد التحرير يتم عبر الطريقة 'Save'. |
| [EncryptedException](./encryptedexception) | الاستثناء الذي يُرمى عندما يحاول المستخدم فتح مستند تم تشفيره باستخدام X509Certificates. |
| [FormFieldManager](./formfieldmanager) | إدارة نموذج باستخدام حقول النماذج القديمة. حقول النماذج القديمة هي أنواع الحقول التي كانت متوفرة في إصدارات سابقة من معالجة Word. مجموعة النماذج القديمة (التي تظهر بعد النقر على أيقونة أدوات النماذج القديمة) تشمل ثلاثة أنواع من حقول النماذج يمكنك إدراجها في مستند: نص، مربع اختيار، قائمة منسدلة، تاريخ، إلخ، راجع المزيد [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype). كل من هذه الحقول يسمح لمستخدم النموذج باختيار أو إدخال معلومات من النوع الذي تراه مناسبًا. |
| [IncorrectPasswordException](./incorrectpasswordexception) | الاستثناء الذي يُرمى عندما تكون كلمة المرور المحددة غير صحيحة. |
| [InvalidFormatException](./invalidformatexception) | الاستثناء الذي يُرمى عندما يحاول المستخدم فتح مستند ما بخيارات خاصة بالصيغ غير متوافقة مع صيغة المستند الأصلي. |
| [License](./license) | يوفر أساليب لترخيص المكوّن. تعرف على المزيد حول الترخيص [هنا](https://purchase.groupdocs.com/faqs/licensing). |
| [Metered](./metered) | يوفر أساليب لتطبيق ترخيص [Metered](https://purchase.groupdocs.com/faqs/licensing/metered). |
| [PasswordRequiredException](./passwordrequiredexception) | الاستثناء الذي يُرمى عندما يحاول المستخدم فتح مستند مشفر محمي بكلمة مرور من صيغة معينة ولا يقدم كلمة مرور لفتح هذا المستند. |

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
