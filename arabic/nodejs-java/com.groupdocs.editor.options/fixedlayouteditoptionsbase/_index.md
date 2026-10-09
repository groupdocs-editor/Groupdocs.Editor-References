---
title: "FixedLayoutEditOptionsBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الفئة المجردة الأساسية للخيارات الخاصة بجميع المستندات ذات الصيغ ذات التخطيط الثابت مثل PDF و XPS."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

الفئة المجردة الأساسية للخيارات الخاصة بجميع المستندات ذات الصيغ ذات التخطيط الثابت مثل PDF و XPS.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | يحصل أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت إلى HTML الناتج. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | يحصل أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت إلى HTML الناتج. |
|
|  | [getPages()](#getPages--) | يسمح بتعيين نطاق الصفحات للمعالجة. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | يسمح بتعيين نطاق الصفحات للمعالجة. |
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


يحصل أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت إلى HTML الناتج. القيمة الافتراضية هي false - يتم الحفاظ على الصور.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


يحصل أو يضبط العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل المستند ذو التخطيط الثابت إلى HTML الناتج. القيمة الافتراضية هي false - يتم الحفاظ على الصور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


يسمح بتعيين نطاق الصفحات للمعالجة. بشكل افتراضي يتم معالجة جميع صفحات المستند ذو التخطيط الثابت.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


يسمح بتعيين نطاق الصفحات للمعالجة. بشكل افتراضي يتم معالجة جميع صفحات المستند ذو التخطيط الثابت.


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

المستندات ذات تنسيق التخطيط الثابت (PDF و XPS على وجه الخصوص) في جوهرها مُقسمة إلى صفحات بشكل صارم، محتواها له تخطيط ثابت ومقسم إلى صفحات. لكن HTML القابل للتحرير الناتج يمكن تمثيله إما في عرض بدون صفحات أو عرض صفحات.

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

المستندات ذات تنسيق التخطيط الثابت (PDF و XPS على وجه الخصوص) في جوهرها مُقسمة إلى صفحات بشكل صارم، محتواها له تخطيط ثابت ومقسم إلى صفحات. لكن HTML القابل للتحرير الناتج يمكن تمثيله إما في عرض بدون صفحات أو عرض صفحات.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

