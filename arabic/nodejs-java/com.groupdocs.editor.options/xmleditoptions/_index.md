---
title: "XmlEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحميل مستندات XML (eXtensible Markup Language) وتحويلها إلى HTML"
type: docs
weight: 51
url: /ar/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحميل XML (eXtensible Markup Language)
المستندات وتحويلها إلى HTML

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الفتح.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الفتح.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | يسمح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | يسمح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | يسمح بتمكين خوارزمية التعرف على URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | يسمح بتمكين خوارزمية التعرف على URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | يسمح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة |
القيم
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | يسمح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة |
القيم
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | يسمح بتمكين قص المسافات الفارغة المتتبعة في العلامة الداخلية |
النص.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | يسمح بتمكين قص المسافات الفارغة المتتبعة في العلامة الداخلية |
النص.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | يسمح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | يسمح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | يسمح بضبط تمييز XML الذي سيُطبق على بنية XML عند تمثيله في HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | يسمح بضبط تنسيق XML الذي سيُطبق على بنية XML عند تمثيله في HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الفتح. بشكل افتراضي يكون null \\u2014 سيتم تطبيق ترميز المستند الداخلي.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الفتح. بشكل افتراضي يكون null \\u2014 سيتم تطبيق ترميز المستند الداخلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


يسمح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة.
بشكل افتراضي يكون معطلاً (false).

*** ** * ** ***


بشكل افتراضي فقط المستندات XML الصحيحة والمصاغة جيداً هي
مقبولة. عندما يتم تمكين هذا الخيار، سيحاول GroupDocs.Editor إصلاح
هيكل XML التالف إذا أمكن.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


يسمح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة.
بشكل افتراضي يكون معطلاً (false).

*** ** * ** ***


بشكل افتراضي فقط المستندات XML الصحيحة والمصاغة جيداً هي
مقبولة. عندما يتم تمكين هذا الخيار، سيحاول GroupDocs.Editor إصلاح
هيكل XML التالف إذا أمكن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


يسمح بتمكين خوارزمية التعرف على URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


يسمح بتمكين خوارزمية التعرف على URI


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


يسمح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة
القيم


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


يسمح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة
القيم


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


يسمح بتمكين قص المسافات الفارغة المتتبعة في العلامة الداخلية
النص. بشكل افتراضي يكون معطلاً (false) \\u2014 سيتم
حفظه.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


يسمح بتمكين قص المسافات الفارغة المتتبعة في العلامة الداخلية
النص. بشكل افتراضي يكون معطلاً (false) \\u2014 سيتم
حفظه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


يسمح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمات. الاقتباسات المزدوجة هي الافتراضية.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


يسمح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمات. الاقتباسات المزدوجة هي الافتراضية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


يسمح بضبط تمييز XML، الذي سيُطبق على هيكل XML، عندما يُعرض في HTML. يتم استخدام التمييز الافتراضي ويمكن تعديله. لا يمكن أن يكون null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


يسمح بضبط تنسيق XML، الذي سيُطبق على هيكل XML، عندما يُعرض في HTML. يتم استخدام التنسيق الافتراضي ويمكن تعديله. لا يمكن أن يكون null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
