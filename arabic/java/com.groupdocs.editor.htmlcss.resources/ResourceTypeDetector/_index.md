---
title: "ResourceTypeDetector"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "طرق ثابتة مساعدة لاكتشاف أنواع الموارد وتنسيقاتها"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

طرق ثابتة مساعدة لاكتشاف أنواع الموارد (الصيغ).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | يكشف عن نوع من اسم ملف محدد ويعيد مثيلًا من |
المقابل IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | يحاول تحليل تدفق إدخال وينشئ أحد تنسيقات HTML المدعومة |
الموارد منه، مع الأخذ في الاعتبار نوعًا افتراضيًا محددًا، إذا كان
ليس null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


يكشف عن نوع من اسم ملف محدد ويعيد مثيلًا من
المقابل IResourceType


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم ملف الإدخال، الذي سيحاول هذه الطريقة استخراج تنفيذ IResourceType الناتج |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


يحاول تحليل تدفق إدخال وينشئ أحد تنسيقات HTML المدعومة
الموارد منه، مع الأخذ في الاعتبار نوعًا افتراضيًا محددًا، إذا كان
ليس null


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | تدفق الإدخال، والذي من المفترض أنه يحتوي على مورد HTML. إذا كان غير صالح، سيتم رمي استثناء. |
|
|  | الاسم | java.lang.String | اسم المورد، الذي سيُستخدم للمورد المُنشأ والمُعاد عند النجاح. لا يمكن أن يكون NULL أو فارغًا أو مسافة |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | الصيغة المفترضة لمورد HTML الإدخال، والتي تكون مفيدة لتحقيق أفضل أداء. إذا كانت غير معروفة تمامًا، استخدم القيمة NULL. قد تكون غير صحيحة، وهذا سيؤدي فقط إلى تدهور الأداء. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

