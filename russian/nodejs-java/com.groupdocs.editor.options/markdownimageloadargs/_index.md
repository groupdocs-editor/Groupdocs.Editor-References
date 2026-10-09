---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Предоставляет данные для события MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /ru/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Предоставляет данные для

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

события.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Получает или задает имя файла (как в документе Markdown), которое будет |
обрабатываться.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Получает или задает имя файла (как в документе Markdown), которое будет |
обрабатываться.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI. |
|
|  | [setData(byte[] data)](#setData-byte---) | Устанавливает пользовательские данные ресурса, которые используются, если |

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


Получает или задает имя файла (как в документе Markdown), которое будет
обрабатываться.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Получает или задает имя файла (как в документе Markdown), которое будет
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
Значение:  true  если у этого изображения есть абсолютная ссылка URI; в противном случае  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Получить значение, указывающее, имеет ли это изображение абсолютную ссылку URI.
Значение:  true  если у этого изображения есть абсолютная ссылка URI; в противном случае  false .


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Устанавливает пользовательские данные ресурса, которые используются, если

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] |  |

