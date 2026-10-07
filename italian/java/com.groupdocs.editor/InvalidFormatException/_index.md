---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "L'eccezione che viene sollevata quando l'utente tenta di aprire un documento con opzioni specifiche del formato incompatibili con il formato originale del documento."
type: docs
weight: 15
url: /it/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

L'eccezione che viene sollevata quando l'utente tenta di aprire un documento con
opzioni specifiche del formato incompatibili con il formato originale del documento.


*** ** * ** ***

Ad esempio, questa eccezione verrà sollevata se si tenta di aprire un documento Spreadsheet con opzioni di documento WordProcessing.

<br />


## Costruttori

| Costruttore | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String |  |
| interno | java.lang.RuntimeException |  |

