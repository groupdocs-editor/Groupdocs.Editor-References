---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Базовый класс для любого поддерживаемого векторного изображения"
type: docs
weight: 13
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Базовый класс для любого поддерживаемого векторного изображения

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [Disposed](#Disposed) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Возвращает имя этого векторного изображения. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Возвращает корректное имя файла этого векторного изображения, которое состоит из имени и |
расширения.
|
|  | [getAspectRatio()](#getAspectRatio--) | Возвращает соотношение сторон этого векторного изображения |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Возвращает линейные размеры этого векторного изображения (ширина и высота) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Проверяет этот экземпляр с указанным на равенство ссылок. |
|
|  | [isDisposed()](#isDisposed--) | Определяет, освобождено ли это растровое изображение, или нет |
|
|  | [getType()](#getType--) | В реализующем типе следует возвращать информацию о типе вектора |
изображение
|
|  | [getByteContent()](#getByteContent--) | В реализующем типе следует возвращать содержимое этого векторного изображения в виде байтов |
поток
|
|  | [getTextContent()](#getTextContent--) | В реализующем типе следует возвращать содержимое этого векторного изображения в виде текста |
форма: base64‑закодированный XML, относящийся к типу изображения
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | В реализующем типе следует сохранять это изображение на диск по указанному пути |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | В реализующем типе следует сохранять текущий векторный образ в растровый PNG |
форматировать в указанный байтовый поток
|
|  | [dispose()](#dispose--) | В реализующем типе следует освобождать этот экземпляр |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Возвращает имя этого векторного изображения. Обычно не содержит имени файла
расширение и теоретически может отличаться от имени файла.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Возвращает корректное имя файла этого векторного изображения, которое состоит из имени и
расширение. Теоретически может отличаться от имени.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Возвращает соотношение сторон этого векторного изображения


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Возвращает линейные размеры этого векторного изображения (ширина и высота)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Проверяет этот экземпляр с указанным на равенство ссылок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Другой экземпляр векторного изображения |
|

**Returns:**
boolean — True, если равны, false, если не равны

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Определяет, освобождено ли это растровое изображение, или нет


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


В реализующем типе следует возвращать информацию о типе вектора
изображение


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


В реализующем типе следует возвращать содержимое этого векторного изображения в виде байтов
поток


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


В реализующем типе следует возвращать содержимое этого векторного изображения в виде текста
форма: base64‑закодированный XML, относящийся к типу изображения


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


В реализующем типе следует сохранять это изображение на диск по указанному пути


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


В реализующем типе следует сохранять текущий векторный образ в растровый PNG
форматировать в указанный байтовый поток


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Байтовый поток, в который будет сохранена PNG‑версия этого растрового изображения. Не должен быть NULL и должен поддерживать запись. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


В реализующем типе следует освобождать этот экземпляр


