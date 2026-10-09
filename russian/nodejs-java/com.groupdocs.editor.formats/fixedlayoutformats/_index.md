---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Инкапсулирует все форматы фиксированного макета, также известные как форматы фиксированных страниц, включая PDF и XPS; не включает растровые изображения."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Инкапсулирует все форматы фиксированного макета (также известные как "fixed-page"), которые включают PDF и XPS (это не включает растровые изображения)

<br />

*** ** * ** ***

Различные приложения для просмотра или публикации документов позволяют пользователям открывать (Adobe Acrobat, XPS Viewer), а иногда редактировать (Adobe InDesign) документы определённых форматов. Эти приложения обычно создают так называемые \u201cfixed-page\u201d документы. Такой формат документа точно описывает, где содержимое документа размещено на каждой странице. Внутри формат PDF или XPS содержит описание каждой страницы, а также инструкции по рисованию, определяющие расположение содержимого на странице. Это аналогично форматам изображений, описывающим, где содержимое отображается в растровой или векторной форме.

<br />


## Поля

| Поле | Описание |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) — тип документа, созданный Adobe в 1990‑х годах. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Получает экземпляр указанного типа [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats), имеющий заданное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) — тип документа, созданный Adobe в 1990‑х годах. Цель этого формата файлов заключалась в введении стандарта представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Получает перечисляемую коллекцию всех [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Значение: IEnumerable{FixedLayoutFormats} содержащий все экземпляры [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Получает экземпляр указанного типа [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats), имеющий заданное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для конвертации. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

