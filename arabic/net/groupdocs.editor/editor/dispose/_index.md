---
title: "Dispose"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحرير هذا المثيل من Editor بحيث يحرّر جميع الموارد الداخلية ويصبح غير متاح للاستخدام لاحقًا."
type: docs
weight: 50
url: /ar/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

يتخلص من هذه النسخة من Editor، بحيث يحرّر جميع الموارد الداخلية ويصبح غير متاح للاستخدام لاحقًا.

```csharp
public void Dispose()
```

### ملاحظات

بعد استدعاء هذه الطريقة، سيؤدي استدعاء أي من الطرق الأخرى لهذا المثيل إلى رمي استثناء ObjectDisposedException. من الآمن استدعاء هذه الطريقة عدة مرات — جميع الاستدعاءات اللاحقة يتم تجاهلها.

### انظر أيضًا

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
