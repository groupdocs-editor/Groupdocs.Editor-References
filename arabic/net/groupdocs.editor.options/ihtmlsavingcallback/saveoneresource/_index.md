---
title: "SaveOneResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "طريقة مثيل يتم استدعاؤها أثناء استدعاء طريقة Savegroupdocs.editor/editabledocument/save ويجب أن ينفذها المستخدم النهائي للحصول على مورد HTML المقدم وحفظه ثم إرجاع رابط لهذا المورد إلى المستدعي."
type: docs
weight: 10
url: /ar/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

طريقة مثيل، يتم استدعاؤها أثناء استدعاء الطريقة [`Save`](../../../groupdocs.editor/editabledocument/save) ويجب أن ينفذها المستخدم النهائي للحصول على مورد HTML المقدم وحفظه ثم إرجاع رابط لهذا المورد إلى المستدعي.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المورد | IHtmlResource | مورد HTML من أي نوع (صور وخطوط، وربما أوراق أنماط إذا لم يتم تضمينها في ترميز HTML)، يتم تمريره من قبل GroupDocs.Editor إلى تنفيذ المستخدم لهذه الواجهة، يحصل عليه المستخدم، ويمكن للمستخدم إجراء أي إجراءات ضرورية مثل الحفظ أو الإرسال أو التحويل وما إلى ذلك. لن يقوم GroupDocs.Editor أبداً بتمرير مورد HTML `null` إلى هذه الطريقة. |

### قيمة الإرجاع

رابط (مرجع) إلى المورد، يتم الحصول عليه في معامل *resource*، يجب على المستخدم تقديمه إلى GroupDocs.Editor، بحيث يقوم GroupDocs.Editor بوضع هذا الرابط في ترميز HTML.

### ملاحظات

يتوقع GroupDocs.Editor أن تنفيذ المستخدم لهذه الطريقة لا يرمي استثناءً أثناء التنفيذ. ومع ذلك، عندما يحدث استثناء، سيكتب GroupDocs.Editor قيمة الخاصية [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) إلى ترميز HTML.

### انظر أيضًا

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
