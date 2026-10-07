---
title: "BmpImage"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет одно изображение в формате BMP BitMap Picture с его метаданными и дополнительными методами"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Представляет одно изображение в формате BMP (BitMap Picture) с его метаданными и
дополнительные методы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр BmpImage из содержимого, представленного в виде base64‑encoded |
строки и с указанным именем
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Создает новый экземпляр BmpImage из содержимого, представленного в виде байтового потока, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным BMP‑изображением |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка в формате base64 действительным BMP‑изображением |
|
|  | [getType()](#getType--) | Возвращает ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Создаёт новый экземпляр BmpImage из содержимого, представленного в виде base64‑encoded
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя BMP‑изображения. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки base64. Не может быть null, пустым или содержать только пробелы. Если содержимое не является BMP, будет выброшено исключение. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Создает новый экземпляр BmpImage из содержимого, представленного в виде байтового потока,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя BMP‑изображения. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать перемещение. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным BMP‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Байтовый поток, который предположительно содержит BMP‑изображение |
|

**Returns:**
boolean — true, если указанный поток содержит действительное BMP‑изображение, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка в формате base64 действительным BMP‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно BMP‑изображения в виде строки base64 |
|

**Returns:**
boolean — true, если указанная строка содержит действительное BMP‑изображение, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
