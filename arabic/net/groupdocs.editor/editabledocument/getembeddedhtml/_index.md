---
title: "GetEmbeddedHtml"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع كل محتوى مستند HTML هذا مع جميع الموارد المرتبطة في شكل سلسلة واحدة حيث يتم تضمين جميع الموارد داخل ترميز HTML بصيغة base64."
type: docs
weight: 150
url: /ar/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

يرجع كل محتوى هذا المستند HTML مع جميع الموارد المرتبطة في شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل ترميز HTML بصيغة مشفرة بقاعدة64.

```csharp
public string GetEmbeddedHtml()
```

### قيمة الإرجاع

سلسلة، لا تكون NULL أو فارغة في أي حال.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ObjectDisposedException | تم التخلص من كائن EditableDocument هذا بالفعل |

### ملاحظات

تحول هذه الطريقة كائن EditableDocument هذا إلى HTML وتسلسله في سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل السلسلة مع علامات HTML:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
