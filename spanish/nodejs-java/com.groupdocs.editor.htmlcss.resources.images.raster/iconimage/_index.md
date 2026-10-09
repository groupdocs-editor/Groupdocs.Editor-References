---
title: "IconImage"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa una imagen en formato ICON con sus metadatos y métodos adicionales"
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Representa una imagen en formato ICON con sus metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de IconImage a partir del contenido, representado como |
cadena codificada en base64, y con el nombre especificado
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de IconImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen ICON válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen ICON válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Devuelve el número de imágenes que están presentes en este archivo ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Crea una nueva instancia de IconImage a partir del contenido, representado como
cadena codificada en base64, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la imagen ICON. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido ICON, se lanzará una excepción. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de IconImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la imagen ICON. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se descarta, este flujo también se descartará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen ICON válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Secuencia de bytes, que presumiblemente contiene una imagen ICON |
|

**Returns:**
boolean - Verdadero si la secuencia especificada contiene una imagen ICON válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen ICON válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen ICON en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen ICON válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Devuelve el número de imágenes que están presentes en este archivo ICON


**Returns:**
int
