---
title: "SvgImage"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один векторный образ в формате SVG (Scalable Vector Graphics) с его метаданными и дополнительными методами"
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Представляет один векторный образ в формате SVG (Scalable Vector Graphics) с его
метаданными и дополнительными методами

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Создаёт новый экземпляр SvgImage из содержимого, представленного в виде обычной строки, |
и с указанным именем
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Создаёт новый экземпляр SvgImage из содержимого, представленного в виде байтового потока, |
и с указанным именем
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Выполняет поверхностную проверку, является ли указанное текстовое содержимое, соответствующее XML, |
представляет SVG‑изображение
|
|  | [getType()](#getType--) | Возвращает ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого SVG‑изображения в виде бинарного потока |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого SVG‑изображения в виде простого текста (в формате XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Возвращает содержимое этого SVG‑изображения в его оригинальном XML‑совместимом виде |
текстовая форма
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет это SVG‑изображение в файл |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Сохраняет это векторное SVG‑изображение в растровое PNG‑изображение |
|
|  | [dispose()](#dispose--) | Уничтожает это растровое изображение, освобождая его содержимое и делая большинство методов |
и свойства нерабочими
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Создаёт новый экземпляр SvgImage из содержимого, представленного в виде обычной строки,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | содержимое | java.lang.String | Содержимое в виде обычной строки, которая содержит корректный XML‑совместимый контент SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. Если это не SVG‑контент, будет выброшено исключение. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Создаёт новый экземпляр SvgImage из содержимого, представленного в виде байтового потока,
и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя SVG‑изображения. Не может быть null, пустым или состоять только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Выполняет поверхностную проверку, является ли указанное текстовое содержимое, соответствующее XML,
представляет SVG‑изображение


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | содержимое | java.lang.String | XML‑контент SVG‑изображения в виде простого текста, а не base64‑закодированного содержимого |
|

**Returns:**
логический тип — True, если указанную строку можно рассматривать как корректный SVG с первого взгляда, false, если это точно не SVG

### getType() {#getType--}
```
public ImageType getType()
```


Возвращает ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Возвращает содержимое этого SVG‑изображения в виде бинарного потока


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Возвращает содержимое этого SVG‑изображения в виде простого текста (в формате XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Возвращает содержимое этого SVG‑изображения в его оригинальном XML‑совместимом виде
текстовая форма


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Сохраняет это SVG‑изображение в файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан (если не существует) или перезаписан (если существует) содержимым этого SVG‑изображения |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Сохраняет это векторное SVG‑изображение в растровое PNG‑изображение


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Выходной поток, в который будет записано содержимое PNG‑изображения. Не может быть NULL и должен быть доступен для записи. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Уничтожает это растровое изображение, освобождая его содержимое и делая большинство методов
и свойства нерабочими


