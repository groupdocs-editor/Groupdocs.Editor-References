---
title: "JpegImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет одно изображение в формате JPEG Joint Photographic Experts Group с его метаданными и дополнительными методами"
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Представляет одно изображение в формате JPEG (Joint Photographic Experts Group) с
его метаданные и дополнительные методы

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
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток корректным JPEG‑изображением |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, корректным JPEG‑изображением |
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
|  | name | java.lang.String | Имя JPEG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоять только из пробелов. Если это не JPEG‑содержимое, будет выброшено исключение. |
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
|  | name | java.lang.String | Имя JPEG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток корректным JPEG‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит JPEG‑изображение |
|

**Returns:**
логический - Истина, если указанный поток содержит корректное JPEG‑изображение, иначе Ложь

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, корректным JPEG‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно JPEG‑изображения в виде строки, закодированной в base64 |
|

**Returns:**
логический - Истина, если указанная строка содержит корректное JPEG‑изображение, иначе Ложь

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
