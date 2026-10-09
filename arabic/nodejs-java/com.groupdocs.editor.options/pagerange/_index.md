---
title: "PageRange"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على نطاق صفحة واحد يمكن أن يكون له حدود مفتوحة أو مغلقة."
type: docs
weight: 27
url: /ar/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

يحتوي على نطاق صفحة واحد، يمكن أن يكون له حدود مفتوحة أو مغلقة. بشكل افتراضي هو "مفتوح بالكامل" - يشمل جميع الصفحات الموجودة. يبدأ ترقيم الصفحات من 1، وليس من 0.

<br />

*** ** * ** ***

هيكل غير قابل للتغيير، يحتوي على نطاق صفحة، لا يرتبط بأي مستند محدد، ويمكنه تمثيل نطاق صفحة لأي مستند.

<br />


## المنشئات

| المنشئ | الوصف |
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
|  | [getStartNumber()](#getStartNumber--) | رقم الصفحة البداية شاملًا، الذي يبدأ منه هذا النطاق. |
|
|  | [getEndNumber()](#getEndNumber--) | رقم الصفحة النهاية حصريًا، الذي يستمر حتى هذا النطاق ويتوقف عنده حصريًا. |
|
|  | [getCount()](#getCount--) | عدد الصفحات داخل النطاق. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كانت هذه الحالة تمثل نطاق صفحات افتراضي "fully open" أي. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | يكشف ما إذا كانت هذه الحالة من PageRange مساوية للمحددة. |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | ينشئ نطاق صفحات يبدأ من الصفحة الأولى ويحتوي على عدد محدد من الصفحات. |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد ويتواصل حتى نهاية المستند. |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية). |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد (شاملاً) ويتواصل حتى رقم الصفحة المحدد (حصريًا). |
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


رقم الصفحة البداية شاملًا، الذي يبدأ منه هذا النطاق. إذا كان 1 - يبدأ النطاق من الصفحة الأولى للمستند.


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


رقم الصفحة النهاية حصريًا، الذي يستمر حتى هذا النطاق ويتوقف عنده حصريًا. إذا كان 0 - يمتد النطاق حتى نهاية المستند.


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


عدد الصفحات داخل النطاق. إذا كان 0 - يمتد النطاق حتى نهاية المستند بغض النظر عن عدد الصفحات التي يتكون منها.


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كانت هذه الحالة تمثل نطاق صفحات افتراضي "fully open" أي أنها تتضمن جميع صفحات المستند.


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


يكشف ما إذا كانت هذه الحالة من PageRange مساوية للمحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | مثال آخر من PageRange للتحقق من المساواة. |
|

**Returns:**
منطقي - true إذا كانا متساويين؛ false إذا كانا غير متساويين.

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


ينشئ نطاق صفحات يبدأ من الصفحة الأولى ويحتوي على عدد محدد من الصفحات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageCount | int | عدد الصفحات، يجب أن يكون أكبر من الصفر. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد ويتواصل حتى نهاية المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر. |
|
|  | pageCount | int | عدد الصفحات، يجب أن يكون أكبر من الصفر. إذا كان الصفر - يعني ذلك جميع الصفحات حتى نهاية المستند. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد (شاملاً) ويتواصل حتى رقم الصفحة المحدد (حصريًا).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPageNumber | int | رقم الصفحة، التي يبدأ منها نطاق الصفحات، شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر. |
|
|  | endPageNumber | int | رقم الصفحة، حتى التي يستمر فيها نطاق الصفحات، حصريًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر، ويجب أيضًا أن تكون أكبر من startPageNumber. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
