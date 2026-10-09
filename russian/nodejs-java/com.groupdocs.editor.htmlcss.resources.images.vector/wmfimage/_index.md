---
title: "WmfImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один векторный образ в формате WMF Windows MetaFile вместе с его метаданными и дополнительными методами"
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Представляет один векторный образ в формате WMF (Windows MetaFile) с его
метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр WmfImage из содержимого, представленного в виде base64‑закодированного |
строки и с указанным именем
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр WmfImage из содержимого, представленного в виде байтового потока, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным WMF‑изображением |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная base64‑закодированная строка действительным WMF‑изображением |
|
|  | [getType()](#getType--) | Возвращает ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого WMF‑изображения в виде бинарного потока |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого WMF‑изображения в виде обычного текста |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет это WMF‑изображение в файл |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Сохраняет это векторное WMF‑изображение в растровое PNG‑изображение |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Сохраняет это векторное WMF‑изображение в векторное SVG‑изображение |
|
|  | [dispose()](#dispose--) | Освобождает это WMF‑изображение, освобождая его содержимое и делая большинство его |
методов и свойств нерабочими
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Создаёт новый экземпляр WmfImage из содержимого, представленного в виде base64‑закодированного
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя WMF‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или состоять только из пробелов. Если это не WMF‑содержимое, будет выброшено исключение. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр WmfImage из содержимого, представленного в виде байтового потока,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя WMF‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным WMF‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Входной байтовый поток. Не может быть NULL, должен поддерживать чтение и перемещение. |
|

**Returns:**
boolean — True, если указанный поток содержит действительное WMF‑изображение, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная base64‑закодированная строка действительным WMF‑изображением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Входная строка, где содержимое WMF‑изображения хранится в base64‑кодировке. Не может быть NULL или пустой. |
|

**Returns:**
boolean — True, если указанная строка содержит действительное WMF‑изображение, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Возвращает содержимое этого WMF‑изображения в виде бинарного потока


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Возвращает содержимое этого WMF‑изображения в виде обычного текста


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Сохраняет это WMF‑изображение в файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан (если не существует) или перезаписан (если существует) содержимым этого WMF‑изображения |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Сохраняет это векторное WMF‑изображение в растровое PNG‑изображение


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Выходной поток, в который будет записано содержимое PNG‑изображения. Не может быть NULL и должен быть доступен для записи. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Сохраняет это векторное WMF‑изображение в векторное SVG‑изображение


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Выходной поток, в который будет записано содержимое SVG‑изображения. Не может быть NULL и должен быть доступен для записи. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает это WMF‑изображение, освобождая его содержимое и делая большинство его
методов и свойств нерабочими


