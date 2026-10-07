---
title: "CSS"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بالحصول على موارد أنماط CSS الخارجية والمضمنة (ولكن ليس المضمنة داخل النص) التي يستخدمها مستند HTML هذا"
type: docs
weight: 60
url: /ar/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

يسمح بالحصول على موارد ورقة الأنماط (CSS) (سواء الخارجية أو المدمجة، ولكن ليس المضمنة داخل النص)، التي يستخدمها هذا المستند HTML

```csharp
public List<CssText> Css { get; }
```

### ملاحظات

هذه الطريقة تُعيد نسخة عميقة من جميع موارد أنماط CSS المستخدمة: `List` هي نسخة جديدة في كل استدعاء، لكن كائنات الموارد هي نفسها.

### انظر أيضًا

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
