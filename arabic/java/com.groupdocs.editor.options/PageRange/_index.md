---
title: "PageRange"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على نطاق صفحة واحد يمكن أن يكون له حدود مفتوحة أو مغلقة."
type: docs
weight: 27
url: /ar/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

يحتوي على نطاق صفحة واحد، يمكن أن يكون له حدود مفتوحة أو مغلقة. بشكل افتراضي يكون \"مفتوحًا بالكامل\" - فهو يشمل جميع الصفحات الموجودة. يبدأ ترقيم الصفحات من 1، وليس من 0.

<br />

*** ** * ** ***

هيكل غير قابل للتغيير، يحتوي على نطاق صفحة، لا يرتبط بأي مستند محدد، ويمكنه تمثيل نطاق صفحة لأي مستند.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [AllPages](#AllPages) | يمثل جميع الصفحات الموجودة في المستند. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | رقم صفحة البداية شامل، الذي يبدأ منه نطاق الصفحة هذا. |
|
|  | [getEndNumber()](#getEndNumber--) | رقم صفحة النهاية حصريًا، الذي يستمر حتى ذلك الرقم ويتوقف عنده حصريًا. |
|
|  | [getCount()](#getCount--) | أعداد الصفحات ضمن النطاق. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كان هذا الكائن يمثل نطاق صفحة افتراضي \"مفتوح بالكامل\" أي. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | يكشف ما إذا كان هذا الكائن من نوع PageRange يساوي المحدد |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | ينشئ نطاق صفحة يبدأ من الصفحة الأولى ويحتوي على عدد محدد من الصفحات |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويستمر حتى نهاية المستند |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد (شاملًا) ويستمر حتى رقم الصفحة المحدد (حصريًا) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


يمثل جميع الصفحات الموجودة في المستند. القيمة الافتراضية.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


رقم صفحة البداية شامل، الذي يبدأ منه نطاق الصفحة هذا. إذا كان 1 - يبدأ نطاق الصفحة من الصفحة الأولى للمستند


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


رقم صفحة النهاية حصريًا، الذي يستمر حتى ذلك الرقم ويتوقف عنده حصريًا. إذا كان 0 - ينتشر نطاق الصفحة حتى نهاية المستند


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


أعداد الصفحات ضمن النطاق. إذا كان 0 - ينتشر نطاق الصفحة حتى نهاية المستند بغض النظر عن عدد الصفحات التي يتكون منها


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كان هذا الكائن يمثل نطاق صفحة افتراضي \"مفتوح بالكامل\" أي أنه يتضمن جميع صفحات المستند


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


يكشف ما إذا كان هذا الكائن من نوع PageRange يساوي المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | كائن PageRange آخر للتحقق من المساواة |
|

**Returns:**
منطقي - true إذا كانا متساويين؛ false إذا كانا غير متساويين

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


ينشئ نطاق صفحة يبدأ من الصفحة الأولى ويحتوي على عدد محدد من الصفحات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageCount | int | عدد الصفحات، يجب أن يكون أكبر من الصفر بشكل صريح |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويستمر حتى نهاية المستند


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صريح |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صريح |
|
|  | pageCount | int | عدد الصفحات، يجب أن يكون أكبر من الصفر بشكل صريح. إذا كان الصفر - فهذا يعني جميع الصفحات حتى نهاية المستند |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد (شاملًا) ويستمر حتى رقم الصفحة المحدد (حصريًا)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صريح |
|
|  | endPageNumber | int | رقم الصفحة، التي يستمر منها نطاق الصفحات، بشكل حصري. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صريح، ويجب أيضًا أن تكون أكبر من startPageNumber بشكل صريح |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
