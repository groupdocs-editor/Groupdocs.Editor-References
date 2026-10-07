---
title: "IconImage"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет одно изображение в формате ICON с его метаданными и дополнительными методами"
type: docs
weight: 12
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Представляет одно изображение в формате ICON с его метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр IconImage из содержимого, представленного как |
строка, закодированная в base64, и с указанным именем
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр IconImage из содержимого, представленного в виде байтового потока, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным изображением ICON |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным изображением ICON |
|
|  | [getType()](#getType--) | Возвращает ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Возвращает количество изображений, присутствующих в этом файле ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Создаёт новый экземпляр IconImage из содержимого, представленного как
строка, закодированная в base64, и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения ICON. Не может быть null, пустым или состоящим только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или состоящим только из пробелов. Если это не содержимое ICON, будет выброшено исключение. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр IconImage из содержимого, представленного в виде байтового потока,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения ICON. Не может быть null, пустым или состоящим только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде байтового потока. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать перемещение. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным изображением ICON


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Байтовый поток, который предположительно содержит изображение ICON |
|

**Returns:**
boolean - True, если указанный поток содержит действительное изображение ICON, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным изображением ICON


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предполагаемого изображения ICON в виде строки, закодированной в base64 |
|

**Returns:**
boolean - True, если указанная строка содержит действительное изображение ICON, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Возвращает количество изображений, присутствующих в этом файле ICON


**Returns:**
int
