---
title: "Dispose"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحرير مثيل مستند Editable هذا، مُحرراً محتواه وجاعلاً طرقه وخصائصه غير عاملة"
type: docs
weight: 110
url: /ar/net/groupdocs.editor/editabledocument/dispose/
---
## EditableDocument.Dispose method

يتخلص من كائن هذا المستند Editable، مما يؤدي إلى التخلص من محتواه وجعل طرقه وخصائصه غير عاملة

```csharp
public void Dispose()
```

### ملاحظات

بعد استدعاء هذه الطريقة، سيؤدي استدعاء أي من الطرق الأخرى لهذا المثيل إلى رمي استثناء ObjectDisposedException. من الآمن استدعاء هذه الطريقة عدة مرات — جميع الاستدعاءات اللاحقة يتم تجاهلها.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
