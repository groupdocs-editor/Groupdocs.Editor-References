---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет одно изображение в формате JPEG Joint Photographic Experts Group с его метаданными и дополнительными методами"
type: docs
weight: 13
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Представляет одно изображение в формате JPEG (Joint Photographic Experts Group) с
его метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр JpegImage из содержимого, представленного как |
строка, закодированная в base64, и с указанным именем
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр JpegImage из содержимого, представленного как поток байтов, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным изображением JPEG |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным изображением JPEG |
|
|  | [getType()](#getType--) | Возвращает ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Создаёт новый экземпляр JpegImage из содержимого, представленного как
строка, закодированная в base64, и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения JPEG. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое JPEG, будет выброшено исключение. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр JpegImage из содержимого, представленного как поток байтов,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения JPEG. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать перемещение. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным изображением JPEG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит изображение JPEG |
|

**Returns:**
boolean - True, если указанный поток содержит корректное изображение JPEG, false в противном случае

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным изображением JPEG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно JPEG‑изображения в виде строки, закодированной в base64 |
|

**Returns:**
boolean - True, если указанная строка содержит корректное изображение JPEG, false в противном случае

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
