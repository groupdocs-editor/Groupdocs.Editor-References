---
title: "FontEmbeddingOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "تتحكم خيارات تضمين الخطوط في أي موارد الخط يجب تضمينها في مستند WordProcessing الناتج"
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

تتحكم خيارات تضمين الخطوط في أي موارد الخط يجب تضمينها في
مستند WordProcessing الناتج


*** ** * ** ***

تُطبق خيارات تضمين الخطوط أثناء حفظ المستند (من EditableDocument الوسيط إلى تنسيق WordProcessing الناتج)، ويُدرج هذا التعداد كخاصية في WordProcessingSaveOptions، حيث يجب استخدامه

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | لا تقم بتضمين أي مورد خط سواءً من EditableDocument أو من |
النظام.
|
|  | [EmbedAll](#EmbedAll) | تحليل محتوى المستند من EditableDocument المدخل، وابحث عن جميع الخطوط المستخدمة |
وتضمينها في مستند WordProcessing الناتج.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | مطابق لـ [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكن استثنِ تلك الخطوط، |
التي يعتبرها نظام التشغيل خطوط نظام
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


لا تقم بتضمين أي مورد خط سواءً من EditableDocument أو من
نظام. القيمة الافتراضية.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


تحليل محتوى المستند من EditableDocument المدخل، وابحث عن جميع الخطوط المستخدمة
وتضمينها في مستند WordProcessing الناتج. في المقام الأول
تأخذ GroupDocs.Editor الخطوط من موارد الخط داخل EditableDocument.
إذا كانت غير كافية أو مفقودة، فإن GroupDocs.Editor يلتقط الخطوط
من نظام التشغيل.


*** ** * ** ***

أولاً، يقوم GroupDocs.Editor بتحليل محتوى EditableDocument ويشكل قائمة بجميع الخطوط المستخدمة. ثم يتم البحث عن هذه الخطوط في موارد الخطوط الخاصة بـ EditableDocument. إذا كان EditableDocument يحتوي على بعض موارد الخطوط التي لا تُستخدم ضمن محتوى المستند، يتم تجاهل هذه الموارد. إذا كان هناك بعض الخطوط المستخدمة في محتوى المستند والتي لا توجد موارد خطوط مقابلة لها في EditableDocument، يحاول GroupDocs.Editor العثور عليها في نظام التشغيل. هذا الخيار يشبه خيار \"Embed fonts in the file\" مع إيقاف تشغيل جميع الخيارات الفرعية في Microsoft Word 2007 وما فوق

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


مطابق لـ [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكن استثنِ تلك الخطوط،
التي يعتبرها نظام التشغيل خطوط نظام


*** ** * ** ***

يحتوي نظام تشغيل MS Windows على مفهوم خطوط النظام، وهي الخطوط الأساسية والأكثر استخدامًا من قبل Windows نفسه. عند استخدام هذا الخيار، يتصرف GroupDocs.Editor كما في حالة [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكنه في النهاية يراجع مجموعة الخطوط التي تم الحصول عليها ويستبعد تلك التي يعتبرها نظام التشغيل خطوط نظام. هذا الخيار يشبه خيار \"Embed fonts in the file\" + \"Do not embed common system fonts\" في Microsoft Word 2007 وما فوق

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
