---
title: "FixedLayoutEditOptionsBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الأساسية المجردة للخيارات الخاصة بجميع المستندات ذات تنسيقات التخطيط الثابت مثل PDF و XPS"
type: docs
weight: 16
url: /ar/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

الفئة الأساسية المجردة للخيارات الخاصة بجميع المستندات ذات تنسيقات التخطيط الثابت مثل PDF و XPS

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | يحصل على أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت المدخل إلى HTML الناتج. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | يحصل على أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت المدخل إلى HTML الناتج. |
|
|  | [getPages()](#getPages--) | يسمح بتحديد نطاق الصفحات للمعالجة. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | يسمح بتحديد نطاق الصفحات للمعالجة. |
|
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


يحصل على أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت المدخل إلى HTML الناتج. القيمة الافتراضية هي false - يتم الحفاظ على الصور.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


يحصل على أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت المدخل إلى HTML الناتج. القيمة الافتراضية هي false - يتم الحفاظ على الصور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


يسمح بتحديد نطاق الصفحات للمعالجة. بشكل افتراضي يتم معالجة جميع صفحات المستند ذو التخطيط الثابت.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


يسمح بتحديد نطاق الصفحات للمعالجة. بشكل افتراضي يتم معالجة جميع صفحات المستند ذو التخطيط الثابت.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (false).

<br />

*** ** * ** ***

المستندات ذات التنسيق الثابت (PDF و XPS على وجه الخصوص) في جوهرها مُقسَّمة إلى صفحات بدقة، ومحتواها له تخطيط ثابت ومقسم إلى صفحات. لكن HTML القابل للتحرير الناتج يمكن تمثيله إما في عرض بدون صفحات أو في عرض صفحي.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (false).

<br />

*** ** * ** ***

المستندات ذات التنسيق الثابت (PDF و XPS على وجه الخصوص) في جوهرها مُقسَّمة إلى صفحات بدقة، ومحتواها له تخطيط ثابت ومقسم إلى صفحات. لكن HTML القابل للتحرير الناتج يمكن تمثيله إما في عرض بدون صفحات أو في عرض صفحي.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

