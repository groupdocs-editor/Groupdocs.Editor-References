---
title: "Save"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحفظ هذا المستند HTML إلى الملف في المسار المحدد حيث سيتم تخزين ترميز HTML وإلى المجلد المصاحب للموارد."
type: docs
weight: 160
url: /ar/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث سيتم تخزين ترميز HTML، وإلى المجلد المصاحب للموارد.

```csharp
public void Save(string htmlFilePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlFilePath | String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. سيتم إنشاء مجلد الموارد المصاحب في نفس المجلد الذي يوجد فيه ملف HTML. |

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث سيتم تخزين ترميز HTML، وإلى المجلد المصاحب للموارد، الذي يقع في المسار المحدد.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlFilePath | String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. لا يمكن أن يكون NULL أو فارغًا. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. |
| resourcesFolderPath | String | المسار الكامل للمجلد المصاحب حيث سيتم تخزين جميع الموارد المرتبطة. إذا كان NULL أو فارغًا، سيتم إنشاء المجلد تلقائيًا في نفس الدليل الذي يوجد فيه ملف *.html. إذا تم تحديده ولم يكن موجودًا، سيتم إنشاؤه. |

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

يحفظ محتوى هذا [`EditableDocument`](../../editabledocument) كمستند HTML إلى كاتب النص المحدد، بينما يسمح معامل الخيارات الثاني بتخصيص عملية الحفظ وتحديد رد الاتصال لحفظ الموارد.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlMarkup | TextWriter | تنفيذ كاتب النص الذي سيُكتب إليه ترميز HTML. لا يمكن أن يكون فارغًا. |
| saveOptions | HtmlSaveOptions | خيارات حفظ HTML التي تتحكم في عملية الحفظ: كيفية تخزين ترميز HTML (أسماء العلامات، أنواع الاقتباس) وكيف وأين سيتم حفظ CSS والموارد الأخرى مثل الصور أو الخطوط. يجب على المستخدم تحديد مُورّث الواجهة في خاصية [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) للتحكم في كيفية حفظ الموارد والإشارة إليها من ترميز HTML. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي من الوسائط المحددة أو خاصية `SavingCallback` في *saveOptions* هي `null` |

### انظر أيضًا

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
