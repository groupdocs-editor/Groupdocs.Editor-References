---
title: "تحرير"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل من الفئة EditableDocumentgroupdocs.editor/editabledocument التي تحتوي بدورها على طرق لإنتاج ترميز HTML والموارد المرتبطة."
type: docs
weight: 60
url: /ar/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل من الفئة '[`EditableDocument`](../../editabledocument)'، التي تحتوي بدورها على طرق لإنتاج ترميز HTML والموارد المرتبطة.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| editOptions | IEditOptions | خيارات المستند الخاصة بالتنسيق، والتي تسمح بضبط عملية التحويل. قد تكون NULL — في هذه الحالة يكتشف GroupDocs.Editor تنسيق المستند المحمَّل مسبقًا ويطبق الخيارات، الافتراضية لهذا التنسيق. يجب ألا تتعارض مع خيارات التحميل المطبقة مسبقًا. |

### قيمة الإرجاع

مثال من الفئة '[`EditableDocument`](../../editabledocument)'، التي تُغلف المستند الإدخالي الكامل مع جميع موارده في تنسيق وسيط. هذه الطريقة، إذا انتهت بنجاح، لا تُعيد NULL أبداً.

### ملاحظات

عند تحميل المستند الأصلي إلى مثيل 'Editor' عبر المُنشئ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيل من فئة 'EditableDocument'. '[`EditableDocument`](../../editabledocument)'، الذي يُرجع من هذه الطريقة، يحتوي على جميع الطرق والخصائص الضرورية لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات اللازمة للتمرير اللاحق إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يحصل على خيارات التحرير، التي تكون محددة لعائلات التنسيقات. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق إنشاء وإرجاع مثال من الفئة '[`EditableDocument`](../../editabledocument)'، التي، بدورها، تحتوي على طرق لإنتاج ترميز HTML والموارد المرتبطة.

```csharp
public EditableDocument Edit()
```

### قيمة الإرجاع

مثال من الفئة '[`EditableDocument`](../../editabledocument)'، التي تُغلف المستند الإدخالي الكامل مع جميع موارده في تنسيق وسيط. هذه الطريقة، إذا انتهت بنجاح، لا تُعيد NULL أبداً.

### ملاحظات

عند تحميل المستند الأصلي إلى مثيل 'Editor' عبر المُنشئ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيل من الفئة '[`EditableDocument`](../../editabledocument)'. '[`EditableDocument`](../../editabledocument)'، الذي يُرجع من هذه الطريقة، يحتوي على جميع الطرق والخصائص الضرورية لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات اللازمة للتمرير اللاحق إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يطبق خيارات التحرير، التي تكون الافتراضية للتنسيق الذي ينتمي إليه المستند الإدخالي. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
