---
title: "InvalidFormatException"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "L'exception qui est levée lorsque l'utilisateur tente d'ouvrir un document avec des options spécifiques au format qui sont incompatibles avec le format du document original."
type: docs
weight: 15
url: /fr/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

L'exception qui est levée lorsque l'utilisateur tente d'ouvrir un document avec
des options spécifiques au format qui sont incompatibles avec le format du document original.


*** ** * ** ***

Par exemple, cette exception sera levée si l'on essaie d'ouvrir un document Spreadsheet avec des options de document WordProcessing.

<br />


## Constructeurs

| Constructeur | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |
| inner | java.lang.RuntimeException |  |

