---
title: "ImageType"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет один поддерживаемый тип изображения, поддерживает как растровые, так и векторные форматы"
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Представляет один поддерживаемый тип изображения (формат), поддерживает как растровые, так и векторные форматы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Неопределённый тип изображения - специальное значение, которое обычно не должно возникать |
|
|  | [getJpeg()](#getJpeg--) | Тип изображения JPEG |
|
|  | [getPng()](#getPng--) | Тип изображения PNG |
|
|  | [getBmp()](#getBmp--) | Тип изображения BMP |
|
|  | [getGif()](#getGif--) | Тип изображения GIF |
|
|  | [getIcon()](#getIcon--) | Тип изображения ICON |
|
|  | [getSvg()](#getSvg--) | Тип векторного изображения SVG |
|
|  | [getWmf()](#getWmf--) | Тип векторного изображения WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | Тип векторного изображения EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | Тип растрового изображения TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Возвращает официальное название этого формата изображения. |
|
|  | [isVector()](#isVector--) | Указывает, является ли данный формат векторным (true) или растровым |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Расширение файла (без начальной точки) конкретного типа изображения |
в нижнем регистре.
|
|  | [toString()](#toString--) | Возвращает свойство FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | MIME‑код конкретного типа изображения в виде строки. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Определяет, равен ли данный экземпляр указанному \"ImageType\" |
экземпляр
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли этот экземпляр указанному неконвертированному объекту, |
который, предположительно, является другим экземпляром \"ImageType\"
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Определяет, равны ли два конкретных экземпляра ImageType |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Определяет, не равны ли два конкретных экземпляра ImageType |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код, который является неизменяемым числом для данного конкретного |
экземпляр
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Возвращает значение ImageType, которое эквивалентно расширению имени файла, которое |
извлекается из указанного имени файла
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Возвращает значение ImageType, которое эквивалентно указанному MIME‑коду |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Неопределённый тип изображения - специальное значение, которое обычно не должно возникать


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


Тип изображения JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


Тип изображения PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


Тип изображения BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


Тип изображения GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


Тип изображения ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


Тип векторного изображения SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


Тип векторного изображения WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


Тип векторного изображения EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


Тип растрового изображения TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Возвращает официальное название этого формата изображения. Никогда не возвращает NULL. Если
экземпляр не повреждён, никогда не генерирует исключение.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Указывает, является ли данный формат векторным (true) или растровым
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Расширение файла (без начальной точки) конкретного типа изображения
в нижнем регистре. Для типа Undefined возвращает строку 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Возвращает свойство FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME‑код конкретного типа изображения в виде строки. Для типа Undefined
возвращает строку 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Определяет, равен ли данный экземпляр указанному \"ImageType\"
экземпляр


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Другой экземпляр ImageType для проверки равенства с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли этот экземпляр указанному неконвертированному объекту,
который, предположительно, является другим экземпляром \"ImageType\"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой экземпляр System.Object, который предположительно имеет тип ImageType, для проверки равенства с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Определяет, равны ли два конкретных экземпляра ImageType


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Первый экземпляр ImageType для проверки |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Второй экземпляр ImageType для проверки |
|

**Returns:**
boolean — True, если равны, false, если не равны

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Определяет, не равны ли два конкретных экземпляра ImageType


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Первый экземпляр ImageType для проверки |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Второй экземпляр ImageType для проверки |
|

**Returns:**
boolean - true, если не равны, false, если равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код, который является неизменяемым числом для данного конкретного
экземпляр


**Returns:**
int — знаковое 4-байтовое целое число

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Возвращает значение ImageType, которое эквивалентно расширению имени файла, которое
извлекается из указанного имени файла


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя файла | java.lang.String | Произвольное имя файла, может быть относительным или полным путём |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Возвращает значение ImageType, которое эквивалентно указанному MIME‑коду


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Произвольный MIME-код |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

