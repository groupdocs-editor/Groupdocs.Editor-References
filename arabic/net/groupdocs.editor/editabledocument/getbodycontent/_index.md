---
title: GetBodyContent
second_title: GroupDocs.Editor لمرجع .NET API
description: إرجاع نص مستند HTML المحتوى بين علامات الفتح والإغلاق BODY بدون هذه العلامات كسلسلة .
type: docs
weight: 120
url: /ar/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

إرجاع نص مستند HTML (المحتوى بين علامات الفتح والإغلاق BODY بدون هذه العلامات) كسلسلة .

```csharp
public string GetBodyContent()
```

### قيمة الإرجاع

سلسلة تحتوي على نص مستند HTML

### ملاحظات

تعمل محررات WYSIWYG مع نص المستند ولا يمكنها معالجة معلومات التعريف الخاصة به بشكل صحيح من كتلة HEAD . تم تصميم هذه الطريقة لمثل هذه الحالات. لا يسمح هذا الحمل الزائد بضبط URI لطلبات الموارد الخارجية.

### أنظر أيضا

* class [EditableDocument](../../editabledocument)
* مساحة الاسم [GroupDocs.Editor](../../editabledocument)
* المجسم [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

إرجاع نص مستند HTML (المحتوى بين علامات الفتح والإغلاق BODY بدون هذه العلامات) كسلسلة ، حيث تحتوي الارتباطات إلى الموارد الخارجية على بادئة محددة.

```csharp
public string GetBodyContent(string externalImagesPrefix)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| externalImagesPrefix | String | من خلال هذه المعلمة المستخدمة يمكن تحديد بادئة ، والتي سيتم إضافتها إلى links لجميع الصور الخارجية في عناصر IMG ، والتي ستكون موجودة في سلسلة HTML الناتجة. إذا كانت NULL أو فارغة ، فلن يتم إضافة البادئات. |

### قيمة الإرجاع

String ، الذي يحتوي على نص مستند HTML مع روابط ، يتم تعديله وفقًا للصور الخارجية

### ملاحظات

تعمل محررات WYSIWYG مع نص المستند ولا يمكنها معالجة معلومات التعريف الخاصة به بشكل صحيح من كتلة HEAD . تم تصميم هذه الطريقة لمثل هذه الحالات. يسمح هذا الحمل الزائد بضبط URIs لطلبات الموارد الخارجية.

### أنظر أيضا

* class [EditableDocument](../../editabledocument)
* مساحة الاسم [GroupDocs.Editor](../../editabledocument)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
