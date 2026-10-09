---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет задавать и настраивать пользовательские параметры для редактирования электронных книг во всех поддерживаемых форматах ePub, MOBI и AZW3."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Позволяет задавать и настраивать пользовательские параметры для редактирования электронных книг во всех поддерживаемых форматах: ePub, MOBI и AZW3.

<br />

*** ** * ** ***

Поддерживаемые форматы электронных книг:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Электронная публикация)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Формат Kindle 8t)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Инициализирует новый экземпляр класса [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), где все параметры установлены в значения по умолчанию |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Инициализирует новый экземпляр класса [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) с указанным режимом пагинации |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Инициализирует новый экземпляр класса [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), где все параметры установлены в значения по умолчанию


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Инициализирует новый экземпляр класса [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) с указанным режимом пагинации


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | enablePagination | boolean | Включает ( true ) или отключает ( false ) пагинацию содержимого электронной книги в результирующем документе HTML. По умолчанию отключено ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено (
false
).

<br />

*** ** * ** ***

По своей сути большинство форматов электронных книг являются потоковым форматом, похожим на Office Open XML, где содержимое представлено как единое целое и разбивается на главы, а не на страницы. Тем не менее, они содержат некоторую информацию, специфичную для страниц, такую как номера страниц, сноски, колонтитулы и т.д. Некоторые читалки электронных книг разбивают содержимое книги на страницы, тогда как другие (особенно мобильные) \\u2014 не делают этого. Эта опция позволяет управлять тем, как содержимое книги должно отображаться в HTML/CSS при редактировании \\u2014 в плавающем ( false ) или постраничном ( true ) виде.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено (
false
).

<br />

*** ** * ** ***

По своей сути большинство форматов электронных книг являются потоковым форматом, похожим на Office Open XML, где содержимое представлено как единое целое и разбивается на главы, а не на страницы. Тем не менее, они содержат некоторую информацию, специфичную для страниц, такую как номера страниц, сноски, колонтитулы и т.д. Некоторые читалки электронных книг разбивают содержимое книги на страницы, тогда как другие (особенно мобильные) \\u2014 не делают этого. Эта опция позволяет управлять тем, как содержимое книги должно отображаться в HTML/CSS при редактировании \\u2014 в плавающем ( false ) или постраничном ( true ) виде.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'.
Эта опция может быть полезна для двустороннего преобразования многоязычных документов. По умолчанию она отключена (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'.
Эта опция может быть полезна для двустороннего преобразования многоязычных документов. По умолчанию она отключена (
false
).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

