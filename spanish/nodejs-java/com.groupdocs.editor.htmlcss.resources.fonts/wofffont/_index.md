---
title: "WoffFont"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa una fuente en el formato WOFF Web Open Font Format"
type: docs
weight: 17
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Representa una fuente en formato WOFF (Web Open Font Format).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Crea una nueva clase WoffFont a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Crea una nueva clase WoffFont a partir del contenido, representado como flujo de bytes, y |
con el nombre especificado
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Tamaño del encabezado WOFF (en bytes), que es necesario para su validación |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una fuente WOFF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una fuente WOFF válida |
|
|  | [getType()](#getType--) | Devuelve FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Crea una nueva clase WoffFont a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la fuente WOFF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido WOFF, se lanzará una excepción. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Crea una nueva clase WoffFont a partir del contenido, representado como flujo de bytes, y
con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la fuente WOFF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Tamaño del encabezado WOFF (en bytes), que es necesario para su validación


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una fuente WOFF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes que presumiblemente contiene un recurso WOFF |
|

**Returns:**
booleano - Verdadero si el flujo especificado contiene una fuente WOFF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una fuente WOFF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta fuente WOFF en forma de cadena codificada en base64 |
|

**Returns:**
booleano - Verdadero si la cadena especificada contiene una fuente WOFF válida, falso en caso contrario

### getType() {#getType--}
```
public FontType getType()
```


Devuelve FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
