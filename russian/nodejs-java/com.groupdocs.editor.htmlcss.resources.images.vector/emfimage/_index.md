---
title: "EmfImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один векторный образ в формате Enhanced Metafile (EMF) с его метаданными и дополнительными методами"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Представляет один векторный образ в формате Enhanced Metafile (EMF) с его
метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр EmfImage из содержимого, представленного в виде base64‑закодированного |
строки и с указанным именем
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр EmfImage из содержимого, представленного в виде байтового потока, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным изображением EMF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная base64‑закодированная строка действительным изображением EMF |
|
|  | [getType()](#getType--) | Возвращает ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого изображения EMF в виде бинарного потока |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого изображения EMF в виде простого текста |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет это изображение EMF в файл |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Сохраняет этот векторный образ EMF в растровое изображение PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Сохраняет этот векторный образ EMF в векторное изображение SVG |
|
|  | [dispose()](#dispose--) | Освобождает ресурсы этого изображения EMF, освобождая его содержимое и делая большую часть его |
методов и свойств нерабочими
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Создаёт новый экземпляр EmfImage из содержимого, представленного в виде base64‑закодированного
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения EMF. Не может быть null, пустым или состоять только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или состоять только из пробелов. Если это не содержимое EMF, будет выброшено исключение. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр EmfImage из содержимого, представленного в виде байтового потока,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя изображения EMF. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным изображением EMF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Входной байтовый поток. Не может быть NULL, должен поддерживать чтение и перемещение. |
|

**Returns:**
boolean — True, если указанный поток содержит действительное изображение EMF, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная base64‑закодированная строка действительным изображением EMF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Входная строка, в которой содержимое изображения EMF хранится в base64‑кодировке. Не может быть NULL или пустой. |
|

**Returns:**
boolean — True, если указанная строка содержит действительное изображение EMF, иначе false

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Возвращает содержимое этого изображения EMF в виде бинарного потока


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Возвращает содержимое этого изображения EMF в виде простого текста


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Сохраняет это изображение EMF в файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан (если он не существует) или перезаписан (если существует) содержимым этого изображения EMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Сохраняет этот векторный образ EMF в растровое изображение PNG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Выходной поток, в который будет записано содержимое PNG‑изображения. Не может быть NULL и должен быть доступен для записи. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Сохраняет этот векторный образ EMF в векторное изображение SVG


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Выходной поток, в который будет записано содержимое SVG‑изображения. Не может быть NULL и должен быть доступен для записи. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает ресурсы этого изображения EMF, освобождая его содержимое и делая большую часть его
методов и свойств нерабочими


