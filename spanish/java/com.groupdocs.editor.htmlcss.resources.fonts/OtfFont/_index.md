---
title: "OtfFont"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una fuente en el formato OTF Open Type Format"
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Representa una fuente en formato OTF (Open Type Format).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Crea una nueva clase OtfFont a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Crea una nueva clase OtfFont a partir del contenido, representado como flujo de bytes, y |
con el nombre especificado
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Tamaño del encabezado OTF (en bytes), que es necesario para su validación |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una fuente OTF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una fuente OTF válida |
|
|  | [getType()](#getType--) | Devuelve |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Crea una nueva clase OtfFont a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente OTF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido OTF, se lanzará una excepción. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Crea una nueva clase OtfFont a partir del contenido, representado como flujo de bytes, y
con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la fuente OTF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Tamaño del encabezado OTF (en bytes), que es necesario para su validación


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una fuente OTF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes que presumiblemente contiene un recurso OTF |
|

**Returns:**
booleano - Verdadero si el flujo especificado contiene una fuente OTF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una fuente OTF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta fuente OTF en forma de cadena codificada en base64 |
|

**Returns:**
booleano - Verdadero si la cadena especificada contiene una fuente OTF válida, falso en caso contrario

### getType() {#getType--}
```
public FontType getType()
```


Devuelve
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
