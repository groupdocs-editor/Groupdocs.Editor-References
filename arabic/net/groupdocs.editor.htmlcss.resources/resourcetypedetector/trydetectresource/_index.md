---
title: "TryDetectResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحاول تحليل تدفق الإدخال وإنشاء أحد موارد HTML المدعومة منه مع مراعاة النوع الافتراضي المحدد إذا لم يكن null."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

يحاول تحليل تدفق الإدخال وإنشاء أحد موارد HTML المدعومة منه، مع مراعاة النوع الافتراضي المحدد إذا لم يكن فارغًا

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputResourceStream | Stream | تدفق الإدخال، الذي من المفترض أنه يحتوي على مورد HTML. إذا كان غير صالح، سيتم إلقاء استثناء. |
| name | String | اسم المورد، الذي سيُستخدم للمورد المُنشأ والمُرجع عند النجاح. لا يمكن أن يكون NULL أو فارغًا أو مسافة بيضاء. |
| assumptiveFormat | IResourceType | الصيغة المفترضة لمورد HTML الإدخالي، والتي تُفيد في تحقيق أفضل أداء. إذا كانت غير معروفة تمامًا، استخدم القيمة NULL. قد تكون غير صحيحة، وهذا سيؤدي فقط إلى تدهور الأداء. |

### قيمة الإرجاع

مثيل يطبق واجهة 'IHtmlResource' ويمثل أحد موارد HTML المدعومة عند النجاح، أو NULL عند الفشل.

### انظر أيضًا

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
