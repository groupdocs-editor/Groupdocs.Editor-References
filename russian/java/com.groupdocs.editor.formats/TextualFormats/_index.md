---
title: "TextualFormats"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует все текстовые форматы, основанные на тексте, включая разметку XML, HTML и другие."
type: docs
weight: 16
url: /ru/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Инкапсулирует все текстовые (основанные на тексте) форматы, включая разметку (XML, HTML) и другие.
Включает следующие форматы:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Поля

| Поле | Описание |
| --- | --- |
|  | [Html](#Html) | Документ HyperText Markup Language (HTML) — это расширение для веб-страниц, созданных для отображения в браузерах. |
|
|  | [Xml](#Xml) | Документ eXtensible Markup Language (XML), который похож на HTML, но отличается использованием тегов для определения объектов. |
|
|  | [Txt](#Txt) | Plain Text Document (TXT) представляет текстовый документ, содержащий простой текст в виде строк. |
|
|  | [Md](#Md) | Markdown — это облегчённый язык разметки для создания форматированного текста с помощью простого текстового редактора. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) — открытый стандартный формат файлов для обмена данными, использующий человекочитаемый текст для хранения и передачи данных. |
|
|  | [Mhtml](#Mhtml) | MIME‑инкапсуляция агрегированных HTML‑документов — это формат архива веб‑страниц, используемый для объединения в одном файле HTML‑кода и сопутствующих ресурсов. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help — проприетарный бинарный формат онлайн‑справки Microsoft, состоящий из набора HTML‑страниц, индекса и других средств навигации. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Получает экземпляр указанного типа [TextualFormats](../../com.groupdocs.editor.formats/textualformats), имеющий указанное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


Документ HyperText Markup Language (HTML) — это расширение для веб-страниц, созданных для отображения в браузерах.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


Документ eXtensible Markup Language (XML), который похож на HTML, но отличается использованием тегов для определения объектов.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) представляет текстовый документ, содержащий простой текст в виде строк.
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown — это облегчённый язык разметки для создания форматированного текста с помощью простого текстового редактора.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) — открытый стандартный формат файлов для обмена данными, использующий человекочитаемый текст для хранения и передачи данных.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME‑инкапсуляция агрегированных HTML‑документов — это формат архива веб‑страниц, используемый для объединения в одном файле HTML‑кода и сопутствующих ресурсов.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help — проприетарный бинарный формат онлайн‑справки Microsoft, состоящий из набора HTML‑страниц, индекса и других средств навигации.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Получает перечисляемую коллекцию всех [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Значение: IEnumerable{TextualFormats} содержащий все экземпляры [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Получает экземпляр указанного типа [TextualFormats](../../com.groupdocs.editor.formats/textualformats), имеющий указанное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

