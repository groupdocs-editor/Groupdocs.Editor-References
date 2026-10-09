---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Исключение, которое выбрасывается при попытке открыть, загрузить, сохранить или обработать каким-либо образом некоторый контент, который предположительно является растровым или векторным изображением, но на самом деле является изображением неожиданного типа или вовсе не изображением."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Исключение, которое выбрасывается при попытке открыть, загрузить, сохранить или обработать
каким-либо другим способом некоторый контент, который предположительно является изображением (растровым или векторным),
но на самом деле является изображением неожиданного типа или вовсе не изображением.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Создаёт новый экземпляр InvalidImageFormatException с указанным сообщением об ошибке |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Создаёт новый экземпляр InvalidImageFormatException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Создаёт новый экземпляр InvalidImageFormatException с указанным сообщением об ошибке


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Текстовое сообщение, описывающее ошибку, может быть null или пустым |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Создаёт новый экземпляр InvalidImageFormatException с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Текстовое сообщение, описывающее ошибку, может быть null или пустым |
|
|  | innerException | java.lang.RuntimeException | Исключение, являющееся причиной текущего исключения, или null‑ссылка, если внутреннее исключение не указано. |
|

