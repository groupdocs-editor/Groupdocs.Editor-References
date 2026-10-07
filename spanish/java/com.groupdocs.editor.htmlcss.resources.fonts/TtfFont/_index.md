---
title: "TtfFont"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una fuente en el formato TTF TrueType Font"
type: docs
weight: 15
url: /es/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Representa una fuente en formato TTF (TrueType Font).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Crea una nueva clase TtfFont a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Crea una nueva clase TtfFont a partir del contenido, representado como flujo de bytes, y |
con el nombre especificado
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Tamaño del encabezado TTF (en bytes), que es necesario para su validación |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una fuente TTF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una fuente TTF válida |
|
|  | [getType()](#getType--) | Devuelve FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Crea una nueva clase TtfFont a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente TTF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido TTF, se lanzará una excepción. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Crea una nueva clase TtfFont a partir del contenido, representado como flujo de bytes, y
con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente TTF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Tamaño del encabezado TTF (en bytes), que es necesario para su validación


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una fuente TTF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes que presumiblemente contiene un recurso TTF |
|

**Returns:**
boolean - Verdadero si la secuencia especificada contiene una fuente TTF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una fuente TTF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta fuente TTF en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una fuente TTF válida, falso en caso contrario

### getType() {#getType--}
```
public FontType getType()
```


Devuelve FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
