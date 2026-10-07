---
title: "IHtmlSavingCallback"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الواجهة التي تُستخدم أثناء حفظ الـ  إلى صيغة HTML والتي يجب أن يُنفذها المستخدم النهائي لحفظ المورد المقدم وإرجاع رابط إليه"
type: docs
weight: 920
url: /ar/net/groupdocs.editor.options/ihtmlsavingcallback/
---
## IHtmlSavingCallback interface

واجهة تُستخدم أثناء حفظ  إلى صيغة HTML ويجب على المستخدم النهائي تنفيذها لحفظ المورد المقدم وإرجاع رابط له.

```csharp
public interface IHtmlSavingCallback
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SaveOneResource](../../groupdocs.editor.options/ihtmlsavingcallback/saveoneresource)(IHtmlResource) | طريقة مثالية، يتم استدعاؤها أثناء استدعاء الطريقة [`Save`](../../groupdocs.editor/editabledocument/save) ويجب أن يُنفذها المستخدم النهائي للحصول على المورد HTML المقدم وحفظه ثم إرجاع رابط لهذا المورد إلى المستدعي. |

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
