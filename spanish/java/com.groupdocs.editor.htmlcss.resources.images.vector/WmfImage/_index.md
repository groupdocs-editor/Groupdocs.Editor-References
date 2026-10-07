---
title: "WmfImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen vectorial en formato WMF Windows MetaFile con sus metadatos y métodos adicionales"
type: docs
weight: 14
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Representa una imagen vectorial en formato WMF (Windows MetaFile) con su
metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de WmfImage a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de WmfImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen WMF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen WMF válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta imagen WMF como un flujo binario |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de esta imagen WMF como texto plano |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda esta imagen WMF en el archivo |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Guarda esta imagen WMF vectorial en una imagen PNG rasterizada |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Guarda esta imagen WMF vectorial en una imagen SVG vectorial |
|
|  | [dispose()](#dispose--) | Elimina esta imagen WMF liberando su contenido y haciendo la mayor parte de su |
métodos y propiedades no funcionen
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Crea una nueva instancia de WmfImage a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen WMF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido WMF, se lanzará una excepción. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de WmfImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen WMF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen WMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes de entrada. No puede ser NULL, debe soportar lectura y búsqueda. |
|

**Returns:**
booleano - Verdadero si el flujo especificado contiene una imagen WMF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen WMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Cadena de entrada, donde el contenido de la imagen WMF está almacenado en codificación base64. No puede ser NULO o vacío. |
|

**Returns:**
booleano - Verdadero si la cadena especificada contiene una imagen WMF válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Devuelve el contenido de esta imagen WMF como un flujo binario


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Devuelve el contenido de esta imagen WMF como texto plano


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Guarda esta imagen WMF en el archivo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado (si no existe) o sobrescrito (si existe) con el contenido de esta imagen WMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Guarda esta imagen WMF vectorial en una imagen PNG rasterizada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flujo de salida, en el que se escribirá el contenido de la imagen PNG. No puede ser NULL y debe ser escribible. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Guarda esta imagen WMF vectorial en una imagen SVG vectorial


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flujo de salida, en el que se escribirá el contenido de la imagen SVG. No puede ser NULL y debe ser escribible. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Elimina esta imagen WMF liberando su contenido y haciendo la mayor parte de su
métodos y propiedades no funcionen


