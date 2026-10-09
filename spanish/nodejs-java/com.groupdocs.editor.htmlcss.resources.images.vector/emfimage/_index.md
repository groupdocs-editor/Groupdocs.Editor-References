---
title: "EmfImage"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa una imagen vectorial en formato Enhanced Metafile (EMF) con sus metadatos y métodos adicionales"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Representa una imagen vectorial en formato Enhanced Metafile (EMF) con su
metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de EmfImage a partir del contenido, representado como base64 codificado |
cadena, y con el nombre especificado
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de EmfImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una imagen EMF válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una imagen EMF válida |
|
|  | [getType()](#getType--) | Devuelve ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta imagen EMF como un flujo binario |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de esta imagen EMF como texto plano |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda esta imagen EMF en el archivo |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Guarda esta imagen vectorial EMF en una imagen raster PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Guarda esta imagen vectorial EMF en una imagen vectorial SVG |
|
|  | [dispose()](#dispose--) | Elimina esta imagen EMF liberando su contenido y haciendo la mayor parte de su |
métodos y propiedades no funcionen
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Crea una nueva instancia de EmfImage a partir del contenido, representado como base64 codificado
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la imagen EMF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido EMF, se lanzará una excepción. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de EmfImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la imagen EMF. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se descarta, este flujo también se descartará. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una imagen EMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes de entrada. No puede ser NULO, debe soportar lectura y búsqueda. |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una imagen EMF válida, falso en caso contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una imagen EMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Cadena de entrada, donde el contenido de la imagen EMF se almacena en codificación base64. No puede ser NULO o vacío. |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una imagen EMF válida, falso en caso contrario

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Devuelve el contenido de esta imagen EMF como un flujo binario


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Devuelve el contenido de esta imagen EMF como texto plano


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Guarda esta imagen EMF en el archivo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado (si no existe) o sobrescrito (si existe) con el contenido de esta imagen EMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Guarda esta imagen vectorial EMF en una imagen raster PNG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flujo de salida, en el que se escribirá el contenido de la imagen PNG. No puede ser NULO y debe ser escribible. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Guarda esta imagen vectorial EMF en una imagen vectorial SVG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flujo de salida, en el que se escribirá el contenido de la imagen SVG. No puede ser NULO y debe ser escribible. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Elimina esta imagen EMF liberando su contenido y haciendo la mayor parte de su
métodos y propiedades no funcionen


