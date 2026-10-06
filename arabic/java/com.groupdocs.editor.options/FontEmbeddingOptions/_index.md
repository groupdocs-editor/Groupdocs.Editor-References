---
title: "FontEmbeddingOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "تتحكم خيارات تضمين الخطوط في الموارد الخطية التي يجب تضمينها في مستند WordProcessing الناتج"
type: docs
weight: 17
url: /ar/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

تتحكم خيارات تضمين الخطوط في الموارد الخطية التي يجب تضمينها في
مستند WordProcessing الناتج


*** ** * ** ***

تُطبق خيارات تضمين الخطوط أثناء حفظ المستند (من EditableDocument الوسيط إلى تنسيق WordProcessing الناتج)، ويتم تضمين هذا التعداد كخاصية في WordProcessingSaveOptions، حيث يجب استخدامه.

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | لا تقم بتضمين أي مورد خط سواءً من EditableDocument أو من الـ |
النظام.
|
|  | [EmbedAll](#EmbedAll) | تحليل محتوى المستند من EditableDocument المدخل، وإيجاد جميع الخطوط المستخدمة |
وتضمينها في مستند WordProcessing الناتج.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | مطابق لـ [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكن استثناء تلك الخطوط، |
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


لا تقم بتضمين أي مورد خط سواءً من EditableDocument أو من الـ
النظام. القيمة الافتراضية.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


تحليل محتوى المستند من EditableDocument المدخل، وإيجاد جميع الخطوط المستخدمة
وتضمينها في مستند WordProcessing الناتج. في المقام الأول
يقوم GroupDocs.Editor بأخذ الخطوط من موارد الخط داخل EditableDocument.
إذا كانت غير كافية أو مفقودة، فإن GroupDocs.Editor يأخذ الخطوط
من نظام التشغيل.


*** ** * ** ***

أولاً، يقوم GroupDocs.Editor بتحليل محتوى EditableDocument ويشكل قائمة بجميع الخطوط المستخدمة. ثم يتم البحث عن هذه الخطوط في موارد الخط داخل EditableDocument. إذا كان EditableDocument يحتوي على بعض موارد الخط التي لا تُستخدم ضمن محتوى المستند، يتم تجاهل تلك الموارد. إذا كانت هناك خطوط مستخدمة في محتوى المستند ولا توجد موارد خطوط مطابقة لها في EditableDocument، يحاول GroupDocs.Editor العثور عليها في نظام التشغيل. هذا الخيار يشبه خيار \"تضمين الخطوط في الملف\" مع إيقاف جميع الخيارات الفرعية في Microsoft Word 2007 وما بعده

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


مطابق لـ [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكن استثناء تلك الخطوط،
التي يعتبرها نظام التشغيل خطوط نظام


*** ** * ** ***

تتضمن MS Windows مفهوم خطوط النظام، وهي الخطوط الأساسية والأكثر استخدامًا من قبل Windows نفسها. عند استخدام هذا الخيار، يتصرف GroupDocs.Editor كما في حالة [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)، لكنه في النهاية يراجع مجموعة الخطوط التي تم الحصول عليها ويستثني تلك التي يعتبرها نظام التشغيل خطوط نظام. هذا الخيار يشبه خيارات \"تضمين الخطوط في الملف\" + \"عدم تضمين خطوط النظام الشائعة\" في Microsoft Word 2007 وما بعده

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
