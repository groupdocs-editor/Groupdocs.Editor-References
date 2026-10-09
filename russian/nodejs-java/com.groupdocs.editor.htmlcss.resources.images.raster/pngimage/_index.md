---
title: "PngImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет одно изображение в формате PNG Portable Network Graphics с его метаданными и дополнительными методами"
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Представляет одно изображение в формате PNG (Portable Network Graphics) с его
метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде base64‑закодированного |
строки и с указанным именем
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде потока байтов, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным изображением PNG |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным изображением PNG |
|
|  | [getType()](#getType--) | Возвращает ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Создаёт новый экземпляр PngImage из содержимого, представленного в виде base64‑закодированного
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения PNG. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое PNG, будет выброшено исключение. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр PngImage из содержимого, представленного в виде потока байтов,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения PNG. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным изображением PNG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит PNG‑изображение |
|

**Returns:**
логический - Истина, если указанный поток содержит корректное PNG‑изображение, иначе Ложь

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным изображением PNG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно PNG‑изображения в виде строки, закодированной в base64 |
|

**Returns:**
логический - Истина, если указанная строка содержит корректное PNG‑изображение, иначе Ложь

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
