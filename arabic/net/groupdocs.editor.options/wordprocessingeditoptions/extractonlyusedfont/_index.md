---
title: "ExtractOnlyUsedFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحصل على أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخراج موارد الخطوط المستخدمة فقط في المحتوى النصي للمستند."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

يحصل على أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخراج موارد الخطوط المستخدمة فقط في المحتوى النصي للمستند.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` إذا كان من الضروري استخراج موارد الخطوط المستخدمة فقط في محتوى النص بالمستند؛ وإلا `false`. القيمة الافتراضية هي `false`.

### ملاحظات

ليس كل الخطوط المستخدمة في مستند WordProcessing تُستَخدم مباشرةً بنسبة 100٪ (مُطبقة على بعض النص). قد يحدث أن يكون الخط مُشارًا إليه في المستند وربما مضمّنًا، لكنه غير مُطبق على أي جزء من النص. على سبيل المثال، قد يكون بعض الخط مُرفقًا بنمط ما، لكن هذا النمط غير مُطبق على أي جزء من النص. هذا الخيار يتحكم في كيفية معالجة مثل هذه الحالات.

### انظر أيضًا

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
