---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor for Java API Reference"
description: "La excepción que se lanza cuando el usuario intenta abrir un documento con opciones específicas de formato que son incompatibles con el formato original del documento."
type: docs
weight: 15
url: /es/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

La excepción que se lanza cuando el usuario intenta abrir un documento con
opciones específicas de formato que son incompatibles con el formato original del documento.


*** ** * ** ***

Por ejemplo, esta excepción se lanzará si se intenta abrir un documento de hoja de cálculo con opciones de documento de procesamiento de texto.

<br />


## Constructores

| Constructor | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String |  |
| interno | java.lang.RuntimeException |  |

