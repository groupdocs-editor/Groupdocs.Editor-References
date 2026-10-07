---
title: "InputControlsClassName"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد اسم فئة سيتم وضعه في سمات الفئة في كل عنصر HTML يمثل حقلًا ما في مستند WordProcessing الإدخالي. بشكل افتراضي يكون NULL ولا تُطبق سمات الفئة."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

يسمح بتحديد اسم فئة سيتم وضعه في سمة 'class' في كل عنصر HTML يمثل حقلًا ما في مستند WordProcessing المدخل. يكون القيمة الافتراضية NULL - لا تُطبق سمات 'class'.

```csharp
public string InputControlsClassName { get; set; }
```

### ملاحظات

تقريبًا جميع الصيغ من عائلة صيغ WordProcessing تحتوي على حقول — كيانات مستندية محددة، تسمح بالحصول على بيانات الإدخال من المستخدمين. هناك مجموعة واسعة من الحقول: صناديق نصية، مربعات اختيار، قوائم منسدلة، أزرار، محددات تاريخ/وقت، إلخ. جميعها تُترجم إلى هياكل وعناصر HTML الأنسب، مع الحفاظ على بيانات المستخدم المدخلة إذا كانت موجودة في المستند الإدخالي. في حالات الاستخدام المحددة قد يكون مطلوبًا جمع البيانات المدخلة على جانب العميل فقط بدلاً من تحرير محتوى المستند بالكامل. لهذه الحالة يُطلب تحديد عناصر التحكم الإدخالية بطريقة ما لجمعها مع بياناتها على جانب العميل. تسمح هذه الخاصية بتحديد اسم فئة سيتم تطبيقه على كل عنصر تحكم إدخالي في ترميز HTML، بحيث يتمكن كود العميل من استعراض بنية مستند HTML وجمع البيانات.

### انظر أيضًا

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
