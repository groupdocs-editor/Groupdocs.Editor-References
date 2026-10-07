---
title: "PngImage"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет одно изображение в формате PNG Portable Network Graphics с его метаданными и дополнительными методами"
type: docs
weight: 14
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
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
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде base64‑encoded |
строки и с указанным именем
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде потока байтов, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток корректным PNG‑изображением |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная base64, корректным PNG‑изображением |
|
|  | [getType()](#getType--) | Возвращает ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Создаёт новый экземпляр PngImage из содержимого, представленного в виде base64‑encoded
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя PNG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной base64. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое PNG, будет выброшено исключение. |
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
|  | name | java.lang.String | Имя PNG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать перемещение. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток корректным PNG‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который, предположительно, содержит изображение PNG |
|

**Returns:**
boolean - True, если указанный поток содержит корректное PNG‑изображение, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная base64, корректным PNG‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно PNG‑изображения в виде строки, закодированной base64 |
|

**Returns:**
boolean - True, если указанная строка содержит корректное PNG‑изображение, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
