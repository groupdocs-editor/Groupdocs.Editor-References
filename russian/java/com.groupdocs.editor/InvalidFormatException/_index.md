---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Исключение, которое выбрасывается, когда пользователь пытается открыть документ с параметрами, специфичными для формата, несовместимыми с оригинальным форматом документа."
type: docs
weight: 15
url: /ru/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Исключение, которое выбрасывается, когда пользователь пытается открыть документ с
параметрами, специфичными для формата, несовместимыми с оригинальным форматом документа.


*** ** * ** ***

Например, это исключение будет выброшено, если попытаться открыть документ Spreadsheet с параметрами документа WordProcessing.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String |  |
| внутренний | java.lang.RuntimeException |  |

