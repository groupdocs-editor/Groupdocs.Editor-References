---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для загрузки XML eXtensible Markup Language документов и их преобразования в HTML"
type: docs
weight: 51
url: /ru/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Позволяет указать пользовательские параметры для загрузки XML (eXtensible Markup Language)
документов и их преобразования в HTML

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Кодировка символов текстового документа, которая будет применена к его |
открытие.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка символов текстового документа, которая будет применена к его |
открытие.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Позволяет включать или отключать механизм исправления повреждённой структуры XML. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Позволяет включать или отключать механизм исправления повреждённой структуры XML. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Позволяет включать алгоритм распознавания URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Позволяет включать алгоритм распознавания URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Позволяет включать алгоритм распознавания адресов электронной почты в атрибуте |
значения
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Позволяет включать алгоритм распознавания адресов электронной почты в атрибуте |
значения
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Позволяет включать обрезку конечных пробелов во внутреннем теге |
текст.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Позволяет включать обрезку конечных пробелов во внутреннем теге |
текст.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Позволяет указывать тип кавычек (одинарные или двойные) для значений атрибутов. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Позволяет указывать тип кавычек (одинарные или двойные) для значений атрибутов. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Позволяет настроить подсветку XML, которая будет применяться к структуре XML при её отображении в HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Позволяет настроить форматирование XML, которое будет применяться к структуре XML при её отображении в HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Кодировка символов текстового документа, которая будет применена к его
открытие. По умолчанию null \\u2014 будет применено внутреннее кодирование документа.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Кодировка символов текстового документа, которая будет применена к его
открытие. По умолчанию null \\u2014 будет применено внутреннее кодирование документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Позволяет включать или отключать механизм исправления повреждённой структуры XML.
По умолчанию отключено (false).

*** ** * ** ***


По умолчанию только корректные, валидные, хорошо сформированные XML‑документы являются
приемлемыми. Когда эта опция включена, GroupDocs.Editor попытается исправить
повреждённую структуру XML, если это возможно.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Позволяет включать или отключать механизм исправления повреждённой структуры XML.
По умолчанию отключено (false).

*** ** * ** ***


По умолчанию только корректные, валидные, хорошо сформированные XML‑документы являются
приемлемыми. Когда эта опция включена, GroupDocs.Editor попытается исправить
повреждённую структуру XML, если это возможно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Позволяет включать алгоритм распознавания URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Позволяет включать алгоритм распознавания URI


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Позволяет включать алгоритм распознавания адресов электронной почты в атрибуте
значения


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Позволяет включать алгоритм распознавания адресов электронной почты в атрибуте
значения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Позволяет включать обрезку конечных пробелов во внутреннем теге
текст. По умолчанию отключено (false) \\u2014 конечные пробелы будут
сохранены.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Позволяет включать обрезку конечных пробелов во внутреннем теге
текст. По умолчанию отключено (false) \\u2014 конечные пробелы будут
сохранены.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Позволяет указывать тип кавычек (одинарные или двойные) для значений атрибутов. По умолчанию двойные кавычки.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Позволяет указывать тип кавычек (одинарные или двойные) для значений атрибутов. По умолчанию двойные кавычки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Позволяет настроить подсветку XML, которая будет применяться к структуре XML при её отображении в HTML. По умолчанию используется подсветка, её можно настроить. Не может быть null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Позволяет настроить форматирование XML, которое будет применяться к структуре XML при её отображении в HTML. По умолчанию используется форматирование, его можно настроить. Не может быть null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
