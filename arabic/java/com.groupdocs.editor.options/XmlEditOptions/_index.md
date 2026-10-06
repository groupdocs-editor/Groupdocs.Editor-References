---
title: "XmlEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحميل مستندات XML (eXtensible Markup Language) وتحويلها إلى HTML"
type: docs
weight: 51
url: /ar/java/com.groupdocs.editor.options/xmleditoptions/
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

| منشئ | الوصف |
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
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | السماح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | السماح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | السماح بتمكين خوارزمية التعرف على URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | السماح بتمكين خوارزمية التعرف على URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | السماح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة |
القيم
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | السماح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة |
القيم
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | السماح بتمكين قص المسافات البيضاء المتتبعة في الوسم الداخلي |
نص.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | السماح بتمكين قص المسافات البيضاء المتتبعة في الوسم الداخلي |
نص.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | السماح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | السماح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | السماح بضبط تمييز XML، الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | السماح بضبط تنسيق XML، الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. |
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
| القيمة | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


السماح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة.
بشكل افتراضي يكون معطلًا (false).

*** ** * ** ***


بشكل افتراضي، فقط مستندات XML صحيحة ومصاغة بشكل سليم هي 
مقبولة. عندما يتم تمكين هذا الخيار، سيحاول GroupDocs.Editor إصلاح 
هيكل XML تالف إذا كان ذلك ممكنًا.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


السماح بتمكين أو تعطيل الآلية لإصلاح بنية XML التالفة.
بشكل افتراضي يكون معطلًا (false).

*** ** * ** ***


بشكل افتراضي، فقط مستندات XML صحيحة ومصاغة بشكل سليم هي 
مقبولة. عندما يتم تمكين هذا الخيار، سيحاول GroupDocs.Editor إصلاح 
هيكل XML تالف إذا كان ذلك ممكنًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


السماح بتمكين خوارزمية التعرف على URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


السماح بتمكين خوارزمية التعرف على URI


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


السماح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة
القيم


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


السماح بتمكين خوارزمية التعرف على عناوين البريد الإلكتروني في السمة
القيم


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


السماح بتمكين قص المسافات البيضاء المتتبعة في الوسم الداخلي
نص. بشكل افتراضي يكون معطلًا (false) \\u2014 سيتم 
محفوظة.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


السماح بتمكين قص المسافات البيضاء المتتبعة في الوسم الداخلي
نص. بشكل افتراضي يكون معطلًا (false) \\u2014 سيتم 
محفوظة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


السماح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. الاقتباسات المزدوجة هي الافتراضية.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


السماح بتحديد نوع الاقتباس (أحادي أو مزدوج) لقيم السمة. الاقتباسات المزدوجة هي الافتراضية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


السماح بضبط تمييز XML، الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. يتم استخدام التمييز الافتراضي ويمكن ضبطه. لا يمكن أن يكون null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


السماح بضبط تنسيق XML، الذي سيُطبق على بنية XML عندما يتم تمثيله في HTML. يتم استخدام التنسيق الافتراضي ويمكن ضبطه. لا يمكن أن يكون null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
