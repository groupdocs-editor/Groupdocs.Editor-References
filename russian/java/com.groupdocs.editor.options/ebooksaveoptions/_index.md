---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для создания и сохранения документа во всех поддерживаемых форматах электронных книг ePub, MOBI и AZW3."
type: docs
weight: 13
url: /ru/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения документа во всех поддерживаемых форматах электронных книг: ePub, MOBI и AZW3.

<br />

*** ** * ** ***

Поддерживаемые форматы электронных книг:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Электронная публикация)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (формат Kindle 8t)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Этот конструктор без параметров создает новый экземпляр EbookSaveOptions с форматом вывода ePub (может быть изменён затем через |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Создаёт новый экземпляр [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) с указанным обязательным форматом вывода электронной книги, при этом все остальные параметры имеют значения по умолчанию |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Указывает максимальный уровень заголовков, при котором файл электронной книги будет разделён. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Указывает максимальный уровень заголовков, при котором файл электронной книги будет разделён. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Указывает, следует ли экспортировать встроенные и пользовательские свойства документа в результирующий файл. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Указывает, следует ли экспортировать встроенные и пользовательские свойства документа в результирующий файл. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Указывает формат результирующего файла электронной книги: IDPF ePub, MOBI или AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Указывает формат результирующего файла электронной книги: IDPF ePub, MOBI или AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Этот конструктор без параметров создает новый экземпляр EbookSaveOptions с форматом вывода ePub (может быть изменён затем через
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Создаёт новый экземпляр [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) с указанным обязательным форматом вывода электронной книги, при этом все остальные параметры имеют значения по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | обязательный формат вывода, в котором следует сохранять электронную книгу |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Указывает максимальный уровень заголовков, при котором файл электронной книги будет разделён. Значение по умолчанию —
2
.
Устанавливая его в
0
отключит разделение, поэтому всё содержимое электронной книги будет включено в один пакет внутри результирующего файла.

<br />

*** ** * ** ***

Когда это свойство установлено в значение от 1 до 9, документ будет разделён по абзацам, отформатированным с помощью

**Heading 1**
,
**Heading 2**
,
**Heading 3**
и т.д. стилей до указанного уровня заголовка.

По умолчанию только
**Heading 1**
и
**Heading 2**
абзацы вызывают разделение документа.
Установка этого свойства в ноль (или значение меньше нуля) полностью отключит разделение документа по абзацам‑заголовкам.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Указывает максимальный уровень заголовков, при котором файл электронной книги будет разделён. Значение по умолчанию —
2
.
Устанавливая его в
0
отключит разделение, поэтому всё содержимое электронной книги будет включено в один пакет внутри результирующего файла.

<br />

*** ** * ** ***

Когда это свойство установлено в значение от 1 до 9, документ будет разделён по абзацам, отформатированным с помощью

**Heading 1**
,
**Heading 2**
,
**Heading 3**
и т.д. стилей до указанного уровня заголовка.

По умолчанию только
**Heading 1**
и
**Heading 2**
абзацы вызывают разделение документа.
Установка этого свойства в ноль (или значение меньше нуля) полностью отключит разделение документа по абзацам‑заголовкам.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Указывает, следует ли экспортировать встроенные и пользовательские свойства документа в результирующий файл.
Значение по умолчанию:
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Указывает, следует ли экспортировать встроенные и пользовательские свойства документа в результирующий файл.
Значение по умолчанию:
false
.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Указывает формат результирующего файла электронной книги: IDPF ePub, MOBI или AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Указывает формат результирующего файла электронной книги: IDPF ePub, MOBI или AZW3.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

