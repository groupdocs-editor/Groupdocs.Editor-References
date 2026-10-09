---
title: "BmpImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет одно изображение в формате BMP BitMap Picture с его метаданными и дополнительными методами"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
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
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр BmpImage из содержимого, представленного как закодированный в base64 |
строки и с указанным именем
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр BmpImage из содержимого, представленного как поток байтов, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным BMP‑изображением |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным BMP‑изображением |
|
|  | [getType()](#getType--) | Возвращает ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Создаёт новый экземпляр BmpImage из содержимого, представленного как закодированный в base64
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя BMP‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоять только из пробелов. Если содержимое не является BMP, будет выброшено исключение. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр BmpImage из содержимого, представленного как поток байтов,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя BMP‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным BMP‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который, предположительно, содержит BMP‑изображение |
|

**Returns:**
boolean — True, если указанный поток содержит действительное BMP‑изображение, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным BMP‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно BMP‑изображения в виде строки, закодированной в base64 |
|

**Returns:**
boolean — True, если указанная строка содержит действительное BMP‑изображение, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
