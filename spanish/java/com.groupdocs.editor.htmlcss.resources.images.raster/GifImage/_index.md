---
title: "GifImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen en formato GIF Graphics Interchange Format con sus metadatos y métodos adicionales"
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Representa una imagen en GIF (Graphics Interchange Format) con su
metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de GifImage a partir del contenido, representado como base64 codificado |
cadena, y con el nombre especificado
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de GifImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen GIF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena base64 codificada especificada es una imagen GIF válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Devuelve la versión interna de esta imagen GIF (la versión se extrae de |
cabecera)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Crea una nueva instancia de GifImage a partir del contenido, representado como base64 codificado
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen GIF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios en blanco. Si no es contenido GIF, se lanzará una excepción. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de GifImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen GIF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen GIF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Secuencia de bytes que presumiblemente contiene una imagen GIF |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una imagen GIF válida, falso de lo contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena base64 codificada especificada es una imagen GIF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen GIF en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen GIF válida, falso de lo contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Devuelve la versión interna de esta imagen GIF (la versión se extrae de
cabecera)


**Returns:**
java.lang.String
