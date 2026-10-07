---
title: "PngImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen en formato PNG Portable Network Graphics con sus metadatos y métodos adicionales"
type: docs
weight: 14
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Representa una imagen en PNG (Portable Network Graphics) con su
metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de PngImage a partir del contenido, representado como base64 |
cadena, y con el nombre especificado
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de PngImage a partir del contenido, representado como secuencia de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen PNG válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen PNG válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Crea una nueva instancia de PngImage a partir del contenido, representado como base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen PNG. No puede ser nulo, vacío o contener solo espacios en blanco. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios en blanco. Si no es contenido PNG, se lanzará una excepción. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de PngImage a partir del contenido, representado como secuencia de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen PNG. No puede ser nulo, vacío o contener solo espacios en blanco. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen PNG válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Secuencia de bytes que presumiblemente contiene una imagen PNG |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una imagen PNG válida, falso de lo contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen PNG válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen PNG en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen PNG válida, falso de lo contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
