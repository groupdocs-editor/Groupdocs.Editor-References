---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen en formato JPEG Joint Photographic Experts Group con sus metadatos y métodos adicionales"
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Representa una imagen en formato JPEG (Joint Photographic Experts Group) con
sus metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de JpegImage a partir del contenido, representado como |
cadena codificada en base64, y con el nombre especificado
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de JpegImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen JPEG válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen JPEG válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Crea una nueva instancia de JpegImage a partir del contenido, representado como
cadena codificada en base64, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen JPEG. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios en blanco. Si no es contenido JPEG, se lanzará una excepción. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de JpegImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen JPEG. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen JPEG válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes que presumiblemente contiene una imagen JPEG |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una imagen JPEG válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen JPEG válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen JPEG en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen JPEG válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
