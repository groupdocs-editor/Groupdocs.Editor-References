---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Предоставляет данные для события MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /ru/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Предоставляет данные для

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

событие.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Получает или задаёт имя файла (как оно указано в Markdown‑документе), которое будет |
обрабатываться.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Получает или задаёт имя файла (как оно указано в Markdown‑документе), которое будет |
обрабатываться.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI. |
|
|  | [setData(byte[] data)](#setData-byte---) | Задаёт пользовательские данные ресурса, которые используются, если |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Получает или задаёт имя файла (как оно указано в Markdown‑документе), которое будет
обрабатываться.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Получает или задаёт имя файла (как оно указано в Markdown‑документе), которое будет
обрабатываться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI.
Значение:  true  если у изображения есть абсолютная ссылка URI; иначе —  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI.
Значение:  true  если у изображения есть абсолютная ссылка URI; иначе —  false .


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Задаёт пользовательские данные ресурса, которые используются, если

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] |  |

