---
title: "EbookEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد وضبط خيارات مخصصة لتحرير مستندات الكتب الإلكترونية بجميع الصيغ المدعومة مثل ePub و MOBI و AZW3."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
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

الصيغ المدعومة للكتب الإلكترونية:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (نشر إلكتروني)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (صيغة Kindle 8t)

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | يُهيئ نسخة جديدة من فئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | يُهيئ نسخة جديدة من فئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) مع وضع ترقيم الصفحات المحدد |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | يحدد ما إذا كان يتم تصدير معلومات اللغة إلى ترميز HTML على شكل سمات HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | يحدد ما إذا كان يتم تصدير معلومات اللغة إلى ترميز HTML على شكل سمات HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


يُهيئ نسخة جديدة من فئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


يُهيئ نسخة جديدة من فئة [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) مع وضع ترقيم الصفحات المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | enablePagination | boolean | يفعل ( true ) أو يعطل ( false ) ترقيم صفحات محتوى الكتاب الإلكتروني في مستند HTML الناتج. بشكل افتراضي يكون معطلاً ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (
false
).

<br />

*** ** * ** ***

في جوهره، معظم صيغ الكتب الإلكترونية داخليًا هي صيغة تدفق مثل Office Open XML، حيث يكون المحتوى صلبًا وينقسم إلى فصول وليس إلى صفحات. ومع ذلك، يحتوي على بعض المعلومات الخاصة بالصفحات مثل أرقام الصفحات، الحواشي، رؤوس/تذييلات الصفحات وما إلى ذلك. بعض قارئات الكتب الإلكترونية تقوم بتقسيم محتوى الكتاب إلى صفحات، بينما البعض الآخر (خاصة على الهواتف المحمولة) \\u2014 لا يفعل ذلك. يتيح هذا الخيار التحكم في كيفية تمثيل محتوى الكتاب الإلكتروني في HTML/CSS أثناء التحرير \\u2014 في العرض العائم ( false ) أو العرض المرقم ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (
false
).

<br />

*** ** * ** ***

في جوهره، معظم صيغ الكتب الإلكترونية داخليًا هي صيغة تدفق مثل Office Open XML، حيث يكون المحتوى صلبًا وينقسم إلى فصول وليس إلى صفحات. ومع ذلك، يحتوي على بعض المعلومات الخاصة بالصفحات مثل أرقام الصفحات، الحواشي، رؤوس/تذييلات الصفحات وما إلى ذلك. بعض قارئات الكتب الإلكترونية تقوم بتقسيم محتوى الكتاب إلى صفحات، بينما البعض الآخر (خاصة على الهواتف المحمولة) \\u2014 لا يفعل ذلك. يتيح هذا الخيار التحكم في كيفية تمثيل محتوى الكتاب الإلكتروني في HTML/CSS أثناء التحرير \\u2014 في العرض العائم ( false ) أو العرض المرقم ( true ).

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


يحدد ما إذا كان يتم تصدير معلومات اللغة إلى ترميز HTML على شكل سمات HTML 'lang'.
قد يكون هذا الخيار مفيدًا لتحويل ذهابًا وإيابًا للمستندات متعددة اللغات. بشكل افتراضي يكون معطلاً (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


يحدد ما إذا كان يتم تصدير معلومات اللغة إلى ترميز HTML على شكل سمات HTML 'lang'.
قد يكون هذا الخيار مفيدًا لتحويل ذهابًا وإيابًا للمستندات متعددة اللغات. بشكل افتراضي يكون معطلاً (
false
).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

