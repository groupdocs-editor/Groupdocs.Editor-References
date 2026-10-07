---
title: "BmpImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen en formato BMP BitMap Picture con sus metadatos y métodos adicionales"
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Representa una imagen en BMP (BitMap Picture) con sus metadatos y
métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de BmpImage a partir del contenido, representado como base64 |
cadena, y con el nombre especificado
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de BmpImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen BMP válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen BMP válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Crea una nueva instancia de BmpImage a partir del contenido, representado como base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen BMP. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido BMP, se lanzará una excepción. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de BmpImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen BMP. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen BMP válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes, que presumiblemente contiene una imagen BMP |
|

**Returns:**
booleano - Verdadero si el flujo especificado contiene una imagen BMP válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen BMP válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta imagen BMP en forma de cadena codificada en base64 |
|

**Returns:**
booleano - Verdadero si la cadena especificada contiene una imagen BMP válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
