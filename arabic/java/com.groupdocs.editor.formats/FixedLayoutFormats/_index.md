---
title: "FixedLayoutFormats"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على جميع تنسيقات التخطيط الثابت المعروفة أيضًا باسم تنسيقات الصفحة الثابتة والتي تشمل PDF و XPS، ولا تشمل الصور النقطية."
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات التخطيط الثابت (المعروفة أيضًا باسم "صفحة ثابتة")، والتي تشمل PDF و XPS (هذا لا يشمل الصور النقطية).

<br />

*** ** * ** ***

تسمح تطبيقات عرض أو نشر المستندات المتنوعة للمستخدمين بفتح (Adobe Acrobat، XPS Viewer)، وأحيانًا تعديل (Adobe InDesign) مستندات ذات تنسيقات محددة. عادةً ما تنتج هذه التطبيقات مستندات بتنسيق \u201cصفحة ثابتة\u201d. يصف مثل هذا التنسيق للمستند بدقة مكان وضع محتوى المستند\u2019 على كل صفحة. داخليًا، يحتوي تنسيق PDF أو XPS على وصف لكل صفحة، بالإضافة إلى تعليمات الرسم التي تحدد تخطيط المحتوى على الصفحة. هذا مشابه لتنسيقات الصور، حيث يصف مكان عرض المحتوى إما بصيغة نقطية أو متجهة.

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Pdf](#Pdf) | تنسيق المستندات القابل للنقل (PDF) هو نوع من المستندات أنشأته شركة Adobe في تسعينيات القرن الماضي. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) التي لها الامتداد المحدد للملف. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


تنسيق المستندات القابل للنقل (PDF) هو نوع من المستندات أنشأته شركة Adobe في تسعينيات القرن الماضي. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق يكون مستقلاً عن برامج التطبيقات، الأجهزة وكذلك نظام التشغيل.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
القيمة: IEnumerable{FixedLayoutFormats} يحتوي على جميع نسخ [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) التي لها الامتداد المحدد للملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | ملحق الملف للتحويل. إذا كان الملحق يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

