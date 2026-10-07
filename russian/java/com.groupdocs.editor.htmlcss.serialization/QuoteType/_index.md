---
title: "QuoteType"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет символы кавычек — одинарную кавычку и двойную кавычку"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Представляет символы кавычек — одинарную кавычку (') и двойную кавычку (\")

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Одинарная кавычка (символ U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Двойная кавычка (символ U+0022 QUOTATION MARK) |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCode()](#getCode--) | Кодовая точка текущего символа (U+0027 или U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Символ для обрамления кавычками |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML‑закодированный символ |
|
|  | [toString()](#toString--) | Возвращает строку "SingleQuote" или "DoubleQuote" в зависимости от текущего значения |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Указывает, равен ли данный экземпляр типа кавычек указанному |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Указывает, равен ли данный экземпляр типа кавычек указанному без приведения типов |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код для этого символа |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Проверяет, равны ли два значения "QuoteType" |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Проверяет, не равны ли два значения "QuoteType" |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Преобразует указанный экземпляр [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) в char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Преобразует конкретный char в соответствующий [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), бросает исключение, если преобразование недопустимо |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Одинарная кавычка (символ U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Двойная кавычка (символ U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Кодовая точка текущего символа (U+0027 или U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Символ для обрамления кавычками


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML‑закодированный символ


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Возвращает строку "SingleQuote" или "DoubleQuote" в зависимости от текущего значения


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Указывает, равен ли данный экземпляр типа кавычек указанному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Другой экземпляр QuoteType для проверки |
|

**Returns:**
boolean — true, если равны, false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, равен ли данный экземпляр типа кавычек указанному без приведения типов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Некастованный объект, ожидается тип [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean — true, если равны, false, если не равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого символа


**Returns:**
int - Hash-code как знаковое целое

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Проверяет, равны ли два значения "QuoteType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Первое значение для проверки |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Второе значение для проверки |
|

**Returns:**
boolean - true если равны, false иначе

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Проверяет, не равны ли два значения "QuoteType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Первое значение для проверки |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Второе значение для проверки |
|

**Returns:**
boolean - false если равны, true иначе

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Преобразует указанный экземпляр [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) в char


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Экземпляр типа QuoteType для приведения |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Преобразует конкретный char в соответствующий [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), бросает исключение, если преобразование недопустимо


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | символ | char | Символ одинарной кавычки (U+0027 APOSTROPHE) или двойной кавычки (U+0022 QUOTATION MARK). Исключение будет выброшено, если будет указано любой другой символ. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
