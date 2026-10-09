---
title: "FontExtractionOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "تتحكم خيارات استخراج الخطوط في أي الخطوط يجب استخراجها ومن أين"
type: docs
weight: 18
url: /ar/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

تتحكم خيارات استخراج الخطوط في أي الخطوط يجب استخراجها ومن
أين

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NotExtract](#NotExtract) | لا يستخرج أي مورد خط سواء من المستند ولا من الـ |
النظام.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | يستخرج جميع موارد الخطوط التي تم تضمينها في مستند Word المدخل |
المستند، بغض النظر عما هو: مخصص أو نظام.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | يستخرج فقط موارد الخط المضمنة التي هي مخصصة (ليس |
نظام)
|
|  | [ExtractAll](#ExtractAll) | يحاول استخراج جميع الخطوط المستخدمة في مستند معالجة الكلمات المدخل |
المستند، بما في ذلك خطوط النظام.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


لا يستخرج أي مورد خط سواء من المستند ولا من الـ
نظام. القيمة الافتراضية.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


يستخرج جميع موارد الخطوط التي تم تضمينها في مستند Word المدخل
المستند، بغض النظر عما هو: مخصص أو نظام.


*** ** * ** ***

يجد المحول ويستخرج جميع موارد الخط بنسبة 100% المضمنة في مستند معالجة الكلمات المدخل، لكنه لا يحدد ما إذا كانت نظامية أم مخصصة؛ ولا يتعامل مع سجل Windows أو مجلدات النظام على الإطلاق.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


يستخرج فقط موارد الخط المضمنة التي هي مخصصة (ليس
نظام)


*** ** * ** ***

يجد المحول ويستخرج جميع موارد الخط المضمنة، ثم يحاول تحديد أي من هذه الخطوط نظامية وأيها ليست كذلك. لتحقيق ذلك، يحاول المحول الحصول على قائمة بجميع خطوط النظام باستخدام سجل Windows ومجلدات النظام، ثم يقارن هذه القائمة بمجموعة الخطوط المضمنة. ونتيجةً لذلك، سيتم إرجاع فقط الجزء الفرعي من تلك الخطوط المضمنة التي لم يتم العثور عليها في النظام.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


يحاول استخراج جميع الخطوط المستخدمة في مستند معالجة الكلمات المدخل
المستند، بما في ذلك خطوط النظام.


*** ** * ** ***

يقوم المحول بتحليل مستند معالجة الكلمات المدخل ويجد جميع الخطوط المستخدمة فيه. إذا كانت جميع هذه الخطوط مضمَّنة في المستند المدخل، يستخرجها المحول ويعيدها. وإلا، إذا لم تغطِ مجموعة الخطوط المضمنة جميع الخطوط المستخدمة في المستند، أو كانت فارغة، يحاول المحول استخراج موارد الخط هذه من النظام باستخدام سجل Windows ومجلدات النظام.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
