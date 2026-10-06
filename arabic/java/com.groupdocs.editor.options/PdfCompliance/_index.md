---
title: "PdfCompliance"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحدد مستوى الامتثال لمعايير PDF"
type: docs
weight: 28
url: /ar/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

يحدد مستوى الامتثال لمعايير PDF

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Pdf17](#Pdf17) | معيار PDF 1.7 (ISO 32000-1) |
|
|  | [Pdf20](#Pdf20) | معيار PDF 2.0 (ISO 32000-2) |
|
|  | [PdfA1a](#PdfA1a) | معيار PDF/A-1a. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | معيار PDF/A-2a (ISO 19005-2). |
|
|  | [PdfA2u](#PdfA2u) | معيار PDF/A-2u (ISO 19005-2). |
|
|  | [PdfUa1](#PdfUa1) | معيار PDF/UA-1 (ISO 14289-1). |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


معيار PDF 1.7 (ISO 32000-1)


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


معيار PDF 2.0 (ISO 32000-2)


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


معيار PDF/A-1a. يتضمن هذا المستوى جميع متطلبات PDF/A-1b ويتطلب إضافيًا تضمين بنية المستند
(المعروفة أيضًا بأنها "موسومة"), بهدف ضمان إمكانية البحث في محتوى المستند وإعادة استخدامه.

<br />

*** ** * ** ***

لاحظ أن تصدير بنية المستند يزيد بشكل كبير من استهلاك الذاكرة، خاصةً بالنسبة للمستندات الكبيرة.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). هدف PDF/A-1b هو ضمان إعادة إنتاج موثوقة للمظهر البصري للمستند.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


معيار PDF/A-2a (ISO 19005-2). يتضمن هذا المستوى جميع متطلبات PDF/A-2u ويتطلب إضافيًا تضمين بنية المستند (المعروفة أيضًا بأنها "موسومة"), بهدف ضمان إمكانية البحث في محتوى المستند وإعادة استخدامه.

<br />

*** ** * ** ***

لاحظ أن تصدير بنية المستند يزيد بشكل كبير من استهلاك الذاكرة، خاصةً بالنسبة للمستندات الكبيرة.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


معيار PDF/A-2u (ISO 19005-2). هدف PDF/A-2u هو الحفاظ على المظهر البصري الثابت للمستند مع مرور الوقت، بغض النظر عن الأدوات والأنظمة المستخدمة لإنشاء الملفات أو تخزينها أو عرضها. بالإضافة إلى ذلك، يمكن استخراج أي نص موجود في المستند بشكل موثوق كسلسلة من نقاط كود Unicode.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


معيار PDF/UA-1 (ISO 14289-1). الغرض الأساسي من PDF/UA هو تحديد كيفية تمثيل المستندات الإلكترونية بصيغة PDF بطريقة تجعل الملف قابلاً للوصول.


