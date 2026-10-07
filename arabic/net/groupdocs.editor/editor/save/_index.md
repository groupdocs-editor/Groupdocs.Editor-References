---
title: "Save"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل المستند المُحرَّر المحدد المُمَثَّل كمثيل من EditableDocumentgroupdocs.editor/editabledocument إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى الدفق المحدد."
type: docs
weight: 80
url: /ar/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

يقوم بتحويل المستند المُحرَّر المحدد، المُمَثَّل كمثيل من '[`EditableDocument`](../../editabledocument)'، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى الدفق المحدد.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputDocument | EditableDocument | إصدار المستند الإدخالي، الذي تم تحريره في محرر HTML WYSIWYG والمخزن كمثيل من الفئة '[`EditableDocument`](../../editabledocument)'، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. يجب ألا يكون فارغًا (null) أو مُحرَّرًا. |
| outputDocument | Stream | دفق الإخراج، الذي سيتم فيه تسجيل محتوى المستند الناتج. يجب ألا يكون فارغًا (null) أو مُحرَّرًا، ويجب أن يدعم الكتابة. |
| saveOptions | ISaveOptions | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك الخيارات العامة والخاصة بالتنسيق. يجب ألا تكون فارغة (null). |

### ملاحظات

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

يقوم بتحويل المستند المُحرَّر المحدد، المُمَثَّل كمثيل من '[`EditableDocument`](../../editabledocument)'، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى ملف بالمسار المحدد.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputDocument | EditableDocument | إصدار المستند الإدخالي، الذي تم تحريره في محرر HTML WYSIWYG والمخزن كمثيل من الفئة '[`EditableDocument`](../../editabledocument)'، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. يجب ألا يكون فارغًا (null) أو مُحرَّرًا. |
| filePath | String | المسار إلى الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم موجود، فسيُستبدل بالكامل. يجب ألا تكون السلسلة التي تمثل المسار فارغة (null) أو خالية أو تحتوي على مسافات بيضاء فقط. |
| saveOptions | ISaveOptions | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك الخيارات العامة والخاصة بالتنسيق. يجب ألا تكون فارغة (null). |

### ملاحظات

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

يقوم بتحويل المستند المُحرَّر المحدد، الممثَّل ككائن من '[`EditableDocument`](../../editabledocument)'، إلى المستند الناتج بصيغة تُحدَّد من امتداد اسم الملف، ويحفظ محتواه إلى ملف بالمسار المحدد.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputDocument | EditableDocument | إصدار المستند الإدخالي، الذي تم تحريره في محرر HTML WYSIWYG والمخزن كمثيل من الفئة '[`EditableDocument`](../../editabledocument)'، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. يجب ألا يكون فارغًا (null) أو مُحرَّرًا. |
| filePath | String | مسار الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم موجود، فسيتم إعادة كتابته بالكامل. يجب ألا تكون سلسلة المسار فارغة أو null أو تحتوي فقط على مسافات بيضاء. نظرًا لأن خيارات الحفظ الافتراضية والصيغة الناتجة تُحدَّدان من اسم هذا الملف، يجب أن يحتوي على امتداد صالح. |

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

يقوم بتحويل المستند الأصلي بعد التعديل (على سبيل المثال، [`FormFieldManager`](../formfieldmanager)) إلى المستند الناتج بالصِيغة المحددة ويحفظ محتواه إلى الدفق المُقدَّم.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputDocument | Stream | الدفق الذي سيُحفظ فيه المستند الناتج. يجب أن يكون هذا الدفق قابلاً للكتابة ومُوضعًا في بداية محتوى المستند. لا يجوز أن يكون null. |
| saveOptions | WordProcessingSaveOptions | خيارات حفظ المستند التي تحدد صيغة المستند الناتج، بالإضافة إلى خيارات الحفظ العامة والخاصة بالصِيغة. لا يجوز أن تكون null. |

### قيمة الإرجاع

الدفق الذي يحتوي على محتوى المستند المحفوظ.

### ملاحظات

إذا كان *outputDocument* أو *saveOptions* null، سيتم رمي استثناء ArgumentNullException. إذا كان المستند المراد حفظه مفقودًا، سيتم رمي استثناء ArgumentNullException.

يُرمي عندما يكون *outputDocument* أو *saveOptions* null، أو عندما يكون المستند المراد حفظه مفقودًا.**تعرف على المزيد:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### انظر أيضًا

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

احفظ محتوى المستند الحالي إلى التيار الخارج المحدد.

```csharp
public Stream Save(Stream outputDocument)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputDocument | Stream | الدفق الذي سيُحفظ فيه محتوى المستند. لا يمكن أن يكون null. |

### قيمة الإرجاع

الدفق الذي يحتوي على محتوى المستند المحفوظ.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمي عندما يكون *outputDocument* null أو إذا كان محتوى المستند مفقودًا. |

### ملاحظات

تنقل هذه الطريقة المحتوى من تمثيل المستند الداخلي إلى الدفق الناتج المقدم. يتم الحفاظ على الموضع الأصلي للدفق بعد عملية الحفظ.

### انظر أيضًا

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
