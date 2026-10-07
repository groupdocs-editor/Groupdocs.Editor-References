---
title: "TiffImage"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет одно изображение в формате TIFF Tagged Image File Format вместе с его метаданными и дополнительными методами"
type: docs
weight: 16
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Представляет одно изображение в формате TIFF (Tagged Image File Format) с его
метаданными и дополнительными методами


*** ** * ** ***

См. https://en.wikipedia.org/wiki/TIFF для подробностей. В очень редких случаях TIFF присутствует внутри документов WordProcessing.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр TiffImage из содержимого, представленного как |
строка, закодированная в base64, и с указанным именем
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Создает новый экземпляр GifImage из содержимого, представленного в виде потока байтов, |
и с указанным именем
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным изображением TIFF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным изображением TIFF |
|
|  | [getType()](#getType--) | Возвращает ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Возвращает количество кадров (изображений) внутри этого изображения TIFF. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Создаёт новый экземпляр TiffImage из содержимого, представленного как
строка, закодированная в base64, и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения TIFF. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое TIFF, будет выброшено исключение. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Создает новый экземпляр GifImage из содержимого, представленного в виде потока байтов,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя GIF‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать перемещение. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным изображением TIFF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит изображение TIFF |
|

**Returns:**
boolean — True, если указанный поток содержит действительное изображение TIFF, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным изображением TIFF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно изображения TIFF в виде строки, закодированной в base64 |
|

**Returns:**
boolean — True, если указанная строка содержит действительное изображение TIFF, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Возвращает количество кадров (изображений) внутри этого изображения TIFF. Не может быть
меньше 1.


**Returns:**
int - 
