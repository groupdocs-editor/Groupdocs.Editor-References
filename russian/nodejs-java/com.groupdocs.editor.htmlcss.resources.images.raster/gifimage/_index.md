---
title: "GifImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет одно изображение в формате GIF Graphics Interchange Format вместе с его метаданными и дополнительными методами"
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Представляет одно изображение в формате GIF (Graphics Interchange Format) вместе с его
метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр GifImage из содержимого, представленного в виде base64-кодированного |
строки и с указанным именем
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр GifImage из содержимого, представленного в виде потока байтов, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток корректным изображением GIF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная base64-кодированная строка корректным изображением GIF |
|
|  | [getType()](#getType--) | Возвращает ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Возвращает внутреннюю версию этого изображения GIF (версия извлекается из |
заголовка)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Создаёт новый экземпляр GifImage из содержимого, представленного в виде base64-кодированного
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения GIF. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде base64-кодированной строки. Не может быть null, пустым или содержать только пробелы. Если это не содержимое GIF, будет выброшено исключение. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр GifImage из содержимого, представленного в виде потока байтов,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения GIF. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток корректным изображением GIF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит изображение GIF |
|

**Returns:**
логический тип - True, если указанный поток содержит корректное изображение GIF, false в противном случае

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная base64-кодированная строка корректным изображением GIF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно изображения GIF в виде строки, закодированной в base64 |
|

**Returns:**
логический тип - True, если указанная строка содержит корректное изображение GIF, false в противном случае

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Возвращает внутреннюю версию этого изображения GIF (версия извлекается из
заголовка)


**Returns:**
java.lang.String
