---
title: "ResourceTypeDetector"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "طرق ثابتة مساعدة لاكتشاف صيغ وأنواع الموارد"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

طرق ثابتة مساعدة لاكتشاف أنواع الموارد (التنسيقات).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | يكتشف النوع من اسم الملف المحدد ويعيد نسخة من |
نوع IResourceType المقابل
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | يحاول تحليل تدفق الإدخال وينشئ أحد موارد HTML المدعومة |
الموارد منه، مع الأخذ في الاعتبار النوع المفترض المحدد، إذا كان
ليس فارغًا
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


يكتشف النوع من اسم الملف المحدد ويعيد نسخة من
نوع IResourceType المقابل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم ملف الإدخال، الذي ستحاول هذه الطريقة استخراج تنفيذ IResourceType الناتج منه |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


يحاول تحليل تدفق الإدخال وينشئ أحد موارد HTML المدعومة
الموارد منه، مع الأخذ في الاعتبار النوع المفترض المحدد، إذا كان
ليس فارغًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | تدفق الإدخال، الذي من المفترض أنه يحتوي على مورد HTML. إذا كان غير صالح، سيتم إلقاء استثناء. |
|
|  | الاسم | java.lang.String | اسم المورد، الذي سيُستخدم للمورد المُنشأ والمرتجع عند النجاح. لا يمكن أن يكون NULL أو فارغًا أو يحتوي على مسافات |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | تنسيق مفترض لمورد HTML المُدخل، وهو مفيد لتحقيق أفضل أداء. إذا كان غير معروف تمامًا، استخدم القيمة NULL. قد يكون غير صحيح، وهذا سيؤدي فقط إلى تدهور الأداء. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

