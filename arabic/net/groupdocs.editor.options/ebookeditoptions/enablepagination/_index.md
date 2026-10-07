---
title: "EnablePagination"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتيح تمكين أو تعطيل الترقيم في مستند HTML الناتج. القيمة الافتراضية هي disabled false."
type: docs
weight: 30
url: /ar/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي معطل (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### ملاحظات

في جوهرها، معظم صيغ الكتب الإلكترونية داخليًا هي صيغة تدفق مثل Office Open XML، حيث يكون المحتوى صلبًا ويتم تقسيمه إلى فصول وليس إلى صفحات. ومع ذلك، تحتوي على بعض المعلومات الخاصة بالصفحات مثل أرقام الصفحات، الحواشي السفلية، رؤوس/تذييلات الصفحات وما إلى ذلك. بعض قارئات الكتب الإلكترونية تقوم بتقسيم محتوى الكتاب إلى صفحات، بينما البعض الآخر (خاصة على الهواتف المحمولة) — لا يفعل ذلك. يتيح هذا الخيار التحكم في كيفية تمثيل محتوى الكتاب الإلكتروني في HTML/CSS أثناء التحرير — في العرض العائم (`false`) أو العرض الصفحي (`true`).

### انظر أيضًا

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
