---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor for Java API Reference"
description: "La excepción que se lanza al intentar abrir, cargar, guardar o procesar de alguna manera algún contenido que presumiblemente es una fuente de formato conocido y soportado, pero que en realidad es una fuente de formato no soportado o inesperado o no es una fuente en absoluto."
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

La excepción que se lanza al intentar abrir, cargar, guardar o procesar de alguna manera algún contenido, que presumiblemente es una fuente de formato soportado (conocido), pero que en realidad es una fuente de formato no soportado o inesperado o no es una fuente en absoluto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Crea una nueva instancia con el mensaje de error especificado |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Crea una nueva instancia de @see \"InvalidFontFormatException\" con el mensaje de error especificado y una referencia a la innerException que es la causa de esta excepción |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Crea una nueva instancia con el mensaje de error especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | Mensaje textual, que describe el error, puede ser nulo o vacío |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Crea una nueva instancia de @see \"InvalidFontFormatException\" con el mensaje de error especificado y una referencia a la innerException que es la causa de esta excepción


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | Mensaje textual, que describe el error, puede ser nulo o vacío |
|
|  | innerException | java.lang.RuntimeException | La excepción que es la causa de la excepción actual, o una referencia nula si no se especifica ninguna innerException. |
|

