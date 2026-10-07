---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует все форматы фиксированной разметки, также известные как форматы fixed-page, которые включают PDF и XPS; это не включает растровые изображения."
type: docs
weight: 12
url: /ru/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Инкапсулирует все форматы фиксированного макета (также известный как "fixed-page"), которые включают PDF и XPS (это не включает растровые изображения)

<br />

*** ** * ** ***

Различные приложения для просмотра или публикации документов позволяют пользователям открывать (Adobe Acrobat, XPS Viewer), а иногда редактировать (Adobe InDesign) документы определённых форматов. Эти приложения обычно создают так называемые «fixed-page» документы. Такой формат документа точно описывает, где размещается содержимое документа на каждой странице. Внутри форматы PDF или XPS содержат описание каждой страницы, а также инструкции по рисованию, указывающие расположение содержимого на странице. Это аналогично форматам изображений, описывающим, где отображается содержимое в растровой или векторной форме.

<br />


## Поля

| Поле | Описание |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) — тип документа, созданный компанией Adobe в 1990-х годах. |
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


Portable Document Format (PDF) — тип документа, созданный компанией Adobe в 1990-х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы.
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Получает перечисляемую коллекцию всех [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Значение: IEnumerable{FixedLayoutFormats}, содержащий все экземпляры [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


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
|  | расширение | java.lang.String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

