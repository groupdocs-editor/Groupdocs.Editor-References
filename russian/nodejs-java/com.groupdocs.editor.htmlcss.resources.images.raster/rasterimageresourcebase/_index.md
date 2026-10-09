---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Базовый класс для любого поддерживаемого растрового изображения с фиксированным именем, размерами, соотношением сторон, типом, размером и содержимым."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Базовый класс для любого поддерживаемого растрового изображения с фиксированным именем, размерами, соотношением
сторон, типом, размером и содержимым.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [Disposed](#Disposed) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Возвращает имя этого растрового изображения. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Возвращает корректное имя файла этого растрового изображения, которое состоит из имени и |
расширения.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Возвращает линейные размеры этого растрового изображения (ширина и высота) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Возвращает соотношение сторон этого изображения как отношение ширины к высоте |
|
|  | [getLength()](#getLength--) | Возвращает длину файла этого растрового изображения в байтах |
|
|  | [getByteContent()](#getByteContent--) | Возвращает содержимое этого растрового изображения в виде потока байтов |
|
|  | [getTextContent()](#getTextContent--) | Возвращает содержимое этого растрового изображения в виде строки, закодированной в base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Сохраняет это растровое изображение в указанный файл |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Проверяет этот экземпляр с указанным на равенство ссылок. |
|
|  | [dispose()](#dispose--) | Уничтожает это растровое изображение, освобождая его содержимое и делая большинство методов |
и свойства нерабочими
|
|  | [isDisposed()](#isDisposed--) | Определяет, освобожден ли этот растровый образ или нет |
|
|  | [getType()](#getType--) | В реализации тип должен возвращать информацию о типе растра |
изображение
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Возвращает имя этого растрового изображения. Обычно не содержит имени файла
расширение и теоретически может отличаться от имени файла.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Возвращает корректное имя файла этого растрового изображения, которое состоит из имени и
расширение. Теоретически может отличаться от имени.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Возвращает линейные размеры этого растрового изображения (ширина и высота)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Возвращает соотношение сторон этого изображения как отношение ширины к высоте


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Возвращает длину файла этого растрового изображения в байтах


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Возвращает содержимое этого растрового изображения в виде потока байтов


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Возвращает содержимое этого растрового изображения в виде строки, закодированной в base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Сохраняет это растровое изображение в указанный файл


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Полный путь к файлу, который будет создан или перезаписан |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Проверяет этот экземпляр с указанным на равенство ссылок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Другой наследник IHtmlResource |
|

**Returns:**
boolean - True, если равны, false, если не равны

### dispose() {#dispose--}
```
public final void dispose()
```


Уничтожает это растровое изображение, освобождая его содержимое и делая большинство методов
и свойства нерабочими


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Определяет, освобожден ли этот растровый образ или нет


**Returns:**
boolean —
### getType() {#getType--}
```
public abstract ImageType getType()
```


В реализации тип должен возвращать информацию о типе растра
изображение


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
