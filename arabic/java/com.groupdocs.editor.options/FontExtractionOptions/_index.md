---
title: "FontExtractionOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "تتحكم خيارات استخراج الخطوط في تحديد الخطوط التي يجب استخراجها ومن أين"
type: docs
weight: 18
url: /ar/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

تتحكم خيارات استخراج الخطوط في تحديد الخطوط التي يجب استخراجها ومن
أين

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NotExtract](#NotExtract) | لا يستخرج أي مورد خط سواء من المستند أو من |
النظام.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | يستخرج جميع موارد الخطوط المضمنة في ملف Word المدخل |
المستند، بغض النظر عن نوعها: مخصصة أو نظامية.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | يستخرج فقط تلك موارد الخطوط المضمنة التي هي مخصصة (ليس |
نظامية)
|
|  | [ExtractAll](#ExtractAll) | يحاول استخراج جميع الخطوط المستخدمة في ملف WordProcessing المدخل |
المستند، بما في ذلك الخطوط النظامية.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


لا يستخرج أي مورد خط سواء من المستند أو من
النظام. القيمة الافتراضية.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


يستخرج جميع موارد الخطوط المضمنة في ملف Word المدخل
المستند، بغض النظر عن نوعها: مخصصة أو نظامية.


*** ** * ** ***

يجد المحول ويستخرج جميع موارد الخط بنسبة 100٪، والتي تم تضمينها في مستند WordProcessing المُدخل، لكنه لا يحدد ما إذا كانت نظامية أم مخصصة؛ ولا يلمس سجل Windows أو مجلدات النظام على الإطلاق.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


يستخرج فقط تلك موارد الخطوط المضمنة التي هي مخصصة (ليس
نظامية)


*** ** * ** ***

يجد المحول ويستخرج جميع موارد الخط المضمنة، ثم يحاول تحديد أي من هذه الخطوط نظامية وأيها ليست كذلك. لتحقيق ذلك، يحاول المحول الحصول على قائمة بجميع الخطوط النظامية باستخدام سجل Windows ومجلدات النظام، ثم يقارن هذه القائمة بمجموعة الخطوط المضمنة. ونتيجةً لذلك، سيتم إرجاع الجزء الفرعي فقط من تلك الخطوط المضمنة التي لم تُعثر عليها في النظام.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


يحاول استخراج جميع الخطوط المستخدمة في ملف WordProcessing المدخل
المستند، بما في ذلك الخطوط النظامية.


*** ** * ** ***

يقوم المحول بتحليل مستند WordProcessing المُدخل ويجد جميع الخطوط المستخدمة فيه. إذا كانت جميع هذه الخطوط مضمَّنة في المستند المُدخل، يستخرجها المحول ويعيدها. وإلا، إذا لم تغطِ مجموعة الخطوط المضمنة جميع الخطوط المستخدمة في المستند، أو كانت فارغة، يحاول المحول استخراج موارد الخط هذه من النظام باستخدام سجل Windows ومجلدات النظام.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
