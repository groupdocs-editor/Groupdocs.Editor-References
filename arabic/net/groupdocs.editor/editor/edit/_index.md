---
title: Edit
second_title: GroupDocs.Editor لمرجع .NET API
description: يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل EditableDocumentgroupdocs.editor/editabledocument فئة  والتي بدورها تحتوي على طرق لإنتاج ترميز HTML والموارد المرتبطة.
type: docs
weight: 50
url: /ar/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل '[`EditableDocument`](../../editabledocument) فئة ، والتي بدورها تحتوي على طرق لإنتاج ترميز HTML والموارد المرتبطة.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| editOptions | IEditOptions | خيارات المستند الخاصة بالتنسيق ، والتي تسمح بضبط عملية التحويل. قد يكون NULL - في هذه الحالة يكتشف GroupDocs.Editor تنسيقًا للمستند الذي تم تحميله مسبقًا ويطبق الخيارات الافتراضية لهذا التنسيق. يجب ألا تتعارض مع خيارات التحميل المطبقة مسبقًا. |

### قيمة الإرجاع

مثيل '[`EditableDocument`](../../editabledocument) class ، والتي تلخص مستند الإدخال الكلي بكل موارده بتنسيق وسيط. هذه الطريقة ، إذا تم الانتهاء بنجاح ، لا ترجع أبدًا NULL.

### ملاحظات

عند تحميل المستند الأصلي المُدخَل إلى مثيل "Editor" من خلال المُنشئ ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط ، والذي يتم تغليفه ضمن مثيل فئة "EditableDocument". "[`EditableDocument`](../../editabledocument)، التي تم إرجاعها من هذه الطريقة ، تحتوي على جميع الأساليب والخصائص اللازمة لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات اللازمة لتمريرها لاحقًا إلى أي محرر WYSIWYG HTML. هذا التحميل الزائد يحصل على خيارات التحرير الخاصة بتنسيقات العائلة.**يتعلم أكثر**

* المزيد حول تحرير المستندات باستخدام GroupDocs.Editor: [كيفية تحرير المستند باستخدام GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### أنظر أيضا

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* مساحة الاسم [GroupDocs.Editor](../../editor)
* المجسم [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق إنشاء وإرجاع مثيل '[`EditableDocument`](../../editabledocument) فئة ، والتي بدورها تحتوي على طرق لإنتاج ترميز HTML والموارد المرتبطة.

```csharp
public EditableDocument Edit()
```

### قيمة الإرجاع

مثيل '[`EditableDocument`](../../editabledocument) class ، والتي تلخص مستند الإدخال الكلي بكل موارده بتنسيق وسيط. هذه الطريقة ، إذا تم الانتهاء بنجاح ، لا ترجع أبدًا NULL.

### ملاحظات

عندما يتم تحميل مستند الإدخال الأصلي إلى مثيل "Editor" من خلال المُنشئ ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط ، والذي يتم تغليفه في مثيل "[`EditableDocument`](../../editabledocument) فصل. "[`EditableDocument`](../../editabledocument)، التي تم إرجاعها من هذه الطريقة ، تحتوي على جميع الأساليب والخصائص اللازمة لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات اللازمة لتمريرها لاحقًا إلى أي محرر WYSIWYG HTML. يطبق هذا التحميل الزائد خيارات التحرير ، والتي تعتبر افتراضية للتنسيق الذي ينتمي إليه مستند الإدخال.**يتعلم أكثر**

* المزيد حول تحرير المستندات باستخدام GroupDocs.Editor: [كيفية تحرير المستند باستخدام GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### أنظر أيضا

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* مساحة الاسم [GroupDocs.Editor](../../editor)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
