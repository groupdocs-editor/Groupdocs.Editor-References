---
title: "GetContent"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع المحتوى الكلي لمستند HTML كتيار بايت عن طريق كتابة هذا المحتوى إلى التيار المحدد باستخدام الترميز النصي المحدد"
type: docs
weight: 130
url: /ar/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

يرجع المحتوى الكلي لمستند HTML كتيار بايت عن طريق كتابة هذا المحتوى إلى التيار المحدد باستخدام الترميز النصي المحدد

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| معامل | الوصف |
| --- | --- |
| TStream | أي تنفيذ لـ Stream |
| storage | دفق بايت غير فارغ يدعم الكتابة |
| encoding | ترميز نص غير فارغ يجب تطبيقه أثناء كتابة محتوى النص إلى *storage* المحدد |

### قيمة الإرجاع

مثال على *storage* المحدد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي من معاملات الإدخال هي null |
| ArgumentException | الدفق المحدد غير قابل للكتابة |

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

يرجع المحتوى الكلي لمستند HTML كسلسلة نصية.

```csharp
public string GetContent()
```

### قيمة الإرجاع

سلسلة، تحتوي على محتوى مستند HTML

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

يرجع المحتوى الكلي لمستند HTML كسلسلة نصية، حيث تحتوي الروابط إلى الموارد الخارجية على القالب المحدد مع العناصر النائبة.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| externalImagesTemplate | String | من خلال هذه المعلمة يمكن للمستخدم تحديد قالب سلسلة يحتوي على عنصر نائب واحد، سيتم تطبيقه على الروابط إلى جميع الصور الخارجية في عناصر IMG التي ستظهر في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن يتم إضافة القالب، وستظهر أسماء الملفات فقط في علامة HTML الناتجة. إذا كان القالب غير صالح، فسيُعامل كبادئة، بحيث تُلحق أسماء الملفات بنهايته. |
| externalCssTemplate | String | من خلال هذه المعلمة يمكن تحديد قالب سلسلة يحتوي على عنصر نائب واحد، سيتم إضافته إلى الروابط لجميع أوراق الأنماط الخارجية في عناصر LINK التي ستكون موجودة في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، فلن يتم إضافة القالب، وستكون أسماء الملفات الصافية موجودة في العلامات HTML الناتجة. إذا كان القالب غير صالح، فسيُعامل كبادئة، وبالتالي سيتم ربط أسماء الملفات بنهايته. |

### قيمة الإرجاع

سلسلة، تحتوي على محتوى مستند HTML مع الروابط، مُعدلة لتتناسب مع الموارد الخارجية

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
