---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor for Java API Reference"
description: "La excepción que se lanza al intentar abrir, cargar, guardar o procesar de alguna manera algún contenido que presumiblemente es una imagen raster o vectorial, pero que en realidad es una imagen de tipo inesperado o no es una imagen en absoluto."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

La excepción que se lanza al intentar abrir, cargar, guardar o procesar
de alguna manera algún contenido, que presumiblemente es una imagen (raster o vectorial),
pero en realidad es una imagen de tipo inesperado o no es una imagen en absoluto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Crea una nueva instancia de InvalidImageFormatException con el mensaje de error especificado |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Crea una nueva instancia de InvalidImageFormatException con el mensaje de error especificado y una referencia a la innerException que es la causa de esta excepción |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Crea una nueva instancia de InvalidImageFormatException con el mensaje de error especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | Mensaje textual, que describe el error, puede ser nulo o vacío |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Crea una nueva instancia de InvalidImageFormatException con el mensaje de error especificado y una referencia a la innerException que es la causa de esta excepción


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | Mensaje textual, que describe el error, puede ser nulo o vacío |
|
|  | innerException | java.lang.RuntimeException | La excepción que es la causa de la excepción actual, o una referencia nula si no se especifica ninguna innerException. |
|

