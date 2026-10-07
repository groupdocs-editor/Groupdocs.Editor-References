---
title: "TiffImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen en formato TIFF Tagged Image File Format con sus metadatos y métodos adicionales"
type: docs
weight: 16
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Representa una imagen en formato TIFF (Tagged Image File Format) con su
metadatos y métodos adicionales


*** ** * ** ***

Ver https://en.wikipedia.org/wiki/TIFF para obtener más detalles. En casos muy raros, TIFF está presente dentro de documentos WordProcessing.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de TiffImage a partir del contenido, representado como |
cadena codificada en base64, y con el nombre especificado
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de GifImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen TIFF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen TIFF válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Devuelve un número de fotogramas (imágenes) dentro de esta imagen TIFF. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Crea una nueva instancia de TiffImage a partir del contenido, representado como
cadena codificada en base64, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen TIFF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido TIFF, se lanzará una excepción. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
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

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen TIFF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes que presumiblemente contiene una imagen TIFF |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una imagen TIFF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen TIFF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen TIFF en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen TIFF válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Devuelve un número de fotogramas (imágenes) dentro de esta imagen TIFF. No puede ser
menor que 1.


**Returns:**
int -
