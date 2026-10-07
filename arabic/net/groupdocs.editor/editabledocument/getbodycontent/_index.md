---
title: "GetBodyContent"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "تُرجع محتوى جسم مستند HTML الداخلي بين وسمي BODY الافتتاحيين والإغلاقيين دون هذه الوسوم كسلسلة."
type: docs
weight: 120
url: /ar/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

يرجع جسم مستند HTML (المحتوى الداخلي بين وسمي BODY الافتتاحية والإغلاقية دون هذه الوسوم) كسلسلة نصية.

```csharp
public string GetBodyContent()
```

### قيمة الإرجاع

سلسلة تحتوي على جسم مستند HTML (بدون وسمي BODY الافتتاحيين والإغلاقيين)

### ملاحظات

معظم محررات WYSIWYG عادةً ما تتعامل مع المحتوى الداخلي لجسم المستند ولا يمكنها معالجة معلومات التعريف الخاصة به من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. هذا التحميل الزائد لا يسمح بتعديل عناوين URI لطلبات الموارد الخارجية.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

يرجع جسم مستند HTML (المحتوى الداخلي بين وسمي BODY الافتتاحية والإغلاقية دون هذه الوسوم) كسلسلة نصية، حيث تحتوي الروابط إلى الموارد الخارجية على القالب المحدد مع العناصر النائبة.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| externalImagesTemplate | String | من خلال هذه المعلمة يمكن للمستخدم تحديد قالب سلسلة يحتوي على عنصر نائب واحد، سيتم تطبيقه على الروابط إلى جميع الصور الخارجية في عناصر IMG التي ستظهر في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن يتم إضافة القالب، وستظهر أسماء الملفات فقط في علامة HTML الناتجة. إذا كان القالب غير صالح، فسيُعامل كبادئة، بحيث تُلحق أسماء الملفات بنهايته. |

### قيمة الإرجاع

سلسلة تحتوي على جسم مستند HTML (بدون وسمي BODY الافتتاحيين والإغلاقيين) مع الروابط، مُعدَّلة للصور الخارجية

### ملاحظات

معظم محررات WYSIWYG عادةً ما تتعامل مع المحتوى الداخلي لجسم المستند ولا يمكنها معالجة معلومات التعريف الخاصة به من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. هذا التحميل الزائد يسمح بتعديل عناوين URI لطلبات الموارد الخارجية.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
