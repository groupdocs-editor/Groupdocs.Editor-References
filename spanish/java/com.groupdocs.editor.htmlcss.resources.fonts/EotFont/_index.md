---
title: "EotFont"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una fuente en el formato EOT Embedded OpenType"
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Representa una fuente en formato EOT (Embedded OpenType).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Crea una nueva clase EotFont a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Crea una nueva clase EotFont a partir del contenido, representado como flujo de bytes, y |
con el nombre especificado
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Tamaño del encabezado EOT (en bytes), que es necesario para su validación |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si la secuencia especificada es una fuente EOT válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una fuente EOT válida |
|
|  | [getType()](#getType--) | Devuelve FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Crea una nueva clase EotFont a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente EOT. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido EOT, se lanzará una excepción. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Crea una nueva clase EotFont a partir del contenido, representado como flujo de bytes, y
con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente EOT. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Tamaño del encabezado EOT (en bytes), que es necesario para su validación


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si la secuencia especificada es una fuente EOT válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Secuencia de bytes que presumiblemente contiene un recurso EOT |
|

**Returns:**
boolean - True si el flujo especificado contiene una fuente EOT válida, false de lo contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una fuente EOT válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta fuente EOT en forma de cadena codificada en base64 |
|

**Returns:**
boolean - True si la cadena especificada contiene una fuente EOT válida, false de lo contrario

### getType() {#getType--}
```
public FontType getType()
```


Devuelve FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
