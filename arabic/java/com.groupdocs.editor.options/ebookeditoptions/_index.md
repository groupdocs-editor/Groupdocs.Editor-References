---
title: "EbookEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد وضبط الخيارات المخصصة لتحرير مستندات الكتب الإلكترونية بجميع الصيغ المدعومة ePub و MOBI و AZW3."
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

يسمح بتحديد وضبط خيارات مخصصة لتحرير مستندات الكتب الإلكترونية بجميع الصيغ المدعومة: ePub، MOBI، و AZW3.

<br />

*** ** * ** ***

صيغ الكتب الإلكترونية المدعومة:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (النشر الإلكتروني)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (صيغة Kindle 8t)

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | ينشئ نسخة جديدة من الفئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية. |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | ينشئ نسخة جديدة من الفئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) مع وضع ترقيم الصفحات المحدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML على شكل سمات HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML على شكل سمات HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


ينشئ نسخة جديدة من الفئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية.


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


ينشئ نسخة جديدة من الفئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) مع وضع ترقيم الصفحات المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | enablePagination | boolean | يفعل ( true ) أو يعطل ( false ) ترقيم صفحات محتوى الكتاب الإلكتروني في مستند HTML الناتج. بشكل افتراضي يكون معطَّلًا ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطَّلًا (
false
).

<br />

*** ** * ** ***

في جوهرها، معظم صيغ الكتب الإلكترونية داخليًا هي صيغة تدفق مثل Office Open XML، حيث يكون المحتوى صلبًا وينقسم إلى فصول وليس إلى صفحات. ومع ذلك، تحتوي على بعض المعلومات الخاصة بالصفحات مثل أرقام الصفحات، الحواشي السفلية، رؤوس/تذييلات الصفحات وما إلى ذلك. بعض قارئات الكتب الإلكترونية تقوم بتقسيم محتوى الكتاب إلى صفحات، بينما البعض الآخر (خاصة على الهواتف المحمولة) \u2014 لا. يتيح هذا الخيار التحكم في كيفية تمثيل محتوى الكتاب الإلكتروني في HTML/CSS أثناء التحرير \u2014 في العرض العائم ( false ) أو الصفحي ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطَّلًا (
false
).

<br />

*** ** * ** ***

في جوهرها، معظم صيغ الكتب الإلكترونية داخليًا هي صيغة تدفق مثل Office Open XML، حيث يكون المحتوى صلبًا وينقسم إلى فصول وليس إلى صفحات. ومع ذلك، تحتوي على بعض المعلومات الخاصة بالصفحات مثل أرقام الصفحات، الحواشي السفلية، رؤوس/تذييلات الصفحات وما إلى ذلك. بعض قارئات الكتب الإلكترونية تقوم بتقسيم محتوى الكتاب إلى صفحات، بينما البعض الآخر (خاصة على الهواتف المحمولة) \u2014 لا. يتيح هذا الخيار التحكم في كيفية تمثيل محتوى الكتاب الإلكتروني في HTML/CSS أثناء التحرير \u2014 في العرض العائم ( false ) أو الصفحي ( true ).

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML على شكل سمات HTML 'lang'.
قد يكون هذا الخيار مفيدًا لتحويل ذهابًا وإيابًا للمستندات متعددة اللغات. بشكل افتراضي يكون معطَّلًا (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML على شكل سمات HTML 'lang'.
قد يكون هذا الخيار مفيدًا لتحويل ذهابًا وإيابًا للمستندات متعددة اللغات. بشكل افتراضي يكون معطَّلًا (
false
).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

