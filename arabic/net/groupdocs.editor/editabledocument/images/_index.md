---
title: "الصور"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بالحصول على موارد الصور الخارجية النقطية والمتجهة التي يستخدمها مستند HTML هذا"
type: docs
weight: 80
url: /ar/net/groupdocs.editor/editabledocument/images/
---
## EditableDocument.Images property

يسمح بالحصول على موارد الصور الخارجية (صور نقطية ومتجهة)، التي يستخدمها هذا المستند HTML

```csharp
public List<IImageResource> Images { get; }
```

### ملاحظات

هذه الطريقة تُعيد نسخة عميقة من جميع موارد الصور المستخدمة: `List` هي نسخة جديدة في كل استدعاء، لكن كائنات الموارد هي نفسها.

### انظر أيضًا

* interface [IImageResource](../../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
