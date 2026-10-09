---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Инкапсулирует все форматы обработки текста."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Инкапсулирует все форматы WordProcessing. Включает следующие типы файлов:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Узнайте больше о форматах Word Processing [здесь](../https://wiki.fileformat.com/word-processing).

Коды MIME берутся из указанных ресурсов:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Поля

| Поле | Описание |
| --- | --- |
|  | [Doc](#Doc) | Бинарный файловый формат MS Word 97-2007 (DOC) представляет документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном формате. |
|
|  | [Docx](#Docx) | Документ Office Open XML WordProcessingML без макросов (DOCX) — известный формат для документов Microsoft Word. |
|
|  | [Dot](#Dot) | Шаблон MS Word 97-2007 (DOT) — это файлы шаблонов, созданные Microsoft Word с предустановленными настройками для создания последующих файлов DOC или DOCX. |
|
|  | [Docm](#Docm) | Файлы Office Open XML WordProcessingML с включёнными макросами (DOCM) — это документы, созданные Microsoft Word 2007 и новее, с возможностью выполнения макросов. |
|
|  | [Dotx](#Dotx) | Шаблон Office Open XML WordprocessingML без макросов (DOTX) — это файлы шаблонов, созданные Microsoft Word с предустановленными настройками для создания последующих файлов DOCX. |
|
|  | [Dotm](#Dotm) | Шаблон Office Open XML WordprocessingML с включёнными макросами (DOTM) представляет файлы шаблонов, созданные Microsoft Word 2007 и новее. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML хранится в виде плоского XML‑файла вместо ZIP‑пакета. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) представляет метод кодирования форматированного текста и графики для использования в приложениях. |
|
|  | [Odt](#Odt) | Файлы Open Document Format Text Document (ODT) — это тип документов, создаваемых текстовыми процессорами, основанными на формате OpenDocument Text. |
|
|  | [Ott](#Ott) | Шаблоны Open Document Format Text Document (OTT) представляют собой шаблоны документов, генерируемые приложениями в соответствии со стандартным форматом OASIS OpenDocument. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Формат — WordProcessingML или WordML (.XML). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Получает экземпляр указанного типа [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats), имеющий указанное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


Бинарный файловый формат MS Word 97-2007 (DOC) представляет документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном формате.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Документ Office Open XML WordProcessingML без макросов (DOCX) — известный формат для документов Microsoft Word.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


Шаблон MS Word 97-2007 (DOT) — это файлы шаблонов, созданные Microsoft Word с предустановленными настройками для создания последующих файлов DOC или DOCX.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Файлы Office Open XML WordProcessingML с включёнными макросами (DOCM) — это документы, созданные Microsoft Word 2007 и новее, с возможностью выполнения макросов.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Шаблон Office Open XML WordprocessingML без макросов (DOTX) — это файлы шаблонов, созданные Microsoft Word с предустановленными настройками для создания последующих файлов DOCX.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Шаблон Office Open XML WordprocessingML с включёнными макросами (DOTM) представляет файлы шаблонов, созданные Microsoft Word 2007 и новее.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML хранится в виде плоского XML‑файла вместо ZIP‑пакета.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) представляет метод кодирования форматированного текста и графики для использования в приложениях.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Файлы Open Document Format Text Document (ODT) — это тип документов, создаваемых текстовыми процессорами, основанными на формате OpenDocument Text.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Шаблоны Open Document Format Text Document (OTT) представляют собой шаблоны документов, генерируемые приложениями в соответствии со стандартным форматом OASIS OpenDocument.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Формат — WordProcessingML или WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Получает перечисляемую коллекцию всех [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Значение: IEnumerable{WordProcessingFormats}, содержащий все экземпляры [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Получает экземпляр указанного типа [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats), имеющий указанное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для конвертации. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

