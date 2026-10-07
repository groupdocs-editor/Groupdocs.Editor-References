---
title: "FromMarkupAndResourceFolder"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "مصنع ثابت ينشئ كائنًا من EditableDocument من علامة HTML محددة ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل"
type: docs
weight: 30
url: /ar/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

مصنع ثابت، ينشئ كائنًا من EditableDocument من ترميز HTML المحدد ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newHtmlContent | String | سلسلة تحتوي على علامة HTML خام يجب تحليلها. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
| resourceFolderPath | String | مسار إلزامي للمجلد الذي يحتوي على الموارد. سيتم استخدام جميع أوراق الأنماط الموجودة في هذا المجلد. لا يمكن أن يكون NULL أو سلسلة فارغة، ويجب أن يكون هذا المجلد موجودًا. |

### قيمة الإرجاع

مثيل جديد غير فارغ من EditableDocument

### ملاحظات

يكون هذا المصنع الثابت مفيدًا عندما يُقدَّم محتوى مستند HTML كسلسلة، لكن جميع الموارد موجودة في مجلد ما، وغالبًا ما تكون الروابط إلى هذه الموارد في علامة HTML غير صالحة أو غير موجودة. عند استدعاء هذه الطريقة، يتم مسح المجلد المحدد وتطبيق جميع أوراق الأنماط التي تم العثور عليها تلقائيًا على المستند. هذه الطريقة مفيدة جدًا عند الحصول على المحتوى من محررات HTML المختلفة، التي عادةً ما تقص بيانات تعريف المستند وما إلى ذلك.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
