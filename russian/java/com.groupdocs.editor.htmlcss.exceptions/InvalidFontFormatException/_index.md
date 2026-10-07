---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Исключение, которое выбрасывается при попытке открыть, загрузить, сохранить или обработать каким‑то образом содержимое, предположительно являющееся шрифтом поддерживаемого известного формата, но на самом деле являющееся шрифтом неподдерживаемого или неожиданного формата или вовсе не шрифтом."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Исключение, которое выбрасывается при попытке открыть, загрузить, сохранить или каким‑то образом обработать содержимое, предположительно являющееся шрифтом поддерживаемого (известного) формата, но на самом деле являющееся шрифтом неподдерживаемого или неожиданного формата или вовсе не шрифтом.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Создаёт новый экземпляр с указанным сообщением об ошибке |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Создаёт новый экземпляр @see "InvalidFontFormatException" с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Создаёт новый экземпляр с указанным сообщением об ошибке


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Текстовое сообщение, описывающее ошибку, может быть null или пустым |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Создаёт новый экземпляр @see "InvalidFontFormatException" с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной данного исключения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Текстовое сообщение, описывающее ошибку, может быть null или пустым |
|
|  | innerException | java.lang.RuntimeException | Исключение, являющееся причиной текущего исключения, или null‑ссылка, если внутреннее исключение не указано. |
|

