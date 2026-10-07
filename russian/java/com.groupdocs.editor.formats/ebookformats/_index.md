---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует все форматы eBook."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Инкапсулирует все eBook‑форматы. Включает следующие типы файлов:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Узнайте больше о формате Mobi [здесь](../https://docs.fileformat.com/ebook/mobi/), и о формате ePub [здесь](../https://docs.fileformat.com/ebook/epub/).

## Поля

| Поле | Описание |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI — это название формата, разработанного для MobiPocket Reader. |
|
|  | [Epub](#Epub) | Формат Electronic Publication (IDPF ePub) — это e‑book формат файла, предоставляющий стандартный цифровой формат публикаций для издателей и потребителей. |
|
|  | [Azw3](#Azw3) | AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата e‑book AZW, разработанного для устройств Amazon Kindle. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Получает экземпляр указанного типа [EBookFormats](../../com.groupdocs.editor.formats/ebookformats), имеющий указанное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI — это название формата, разработанного для MobiPocket Reader. Также называется PRC, AZW.
В настоящее время он используется Amazon с немного иной схемой DRM и называется AZW.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Формат Electronic Publication (IDPF ePub) — это e‑book формат файла, предоставляющий стандартный цифровой формат публикаций для издателей и потребителей.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата e‑book AZW, разработанного для устройств Amazon Kindle.
Этот формат является улучшением более старых файлов AZW.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Получает перечисляемую коллекцию всех [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Значение: IEnumerable{EBookFormats}, содержащий все экземпляры [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Получает экземпляр указанного типа [EBookFormats](../../com.groupdocs.editor.formats/ebookformats), имеющий указанное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

