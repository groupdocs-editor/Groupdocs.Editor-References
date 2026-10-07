---
title: "SvgImage"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una imagen vectorial en formato SVG Scalable Vector Graphics con sus metadatos y métodos adicionales"
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Representa una imagen vectorial en formato SVG (Scalable Vector Graphics) con su
metadatos y métodos adicionales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Crea una nueva instancia de SvgImage a partir del contenido, representado como cadena habitual, |
y con el nombre especificado
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Crea una nueva instancia de SvgImage a partir del contenido, representado como flujo de bytes, |
y con el nombre especificado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Realiza una verificación superficial de si el contenido textual especificado, compatible con XML |
representa una imagen SVG
|
|  | [getType()](#getType--) | Devuelve ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta imagen SVG como un flujo binario |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de esta imagen SVG como texto plano (en formato XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Devuelve el contenido de esta imagen SVG en su formato original compatible con XML |
forma textual
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda esta imagen SVG en el archivo |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Guarda esta imagen SVG vectorial en una imagen PNG rasterizada |
|
|  | [dispose()](#dispose--) | Descarta esta imagen rasterizada, descartando su contenido y haciendo que la mayoría de los métodos |
y propiedades no funcionales
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Crea una nueva instancia de SvgImage a partir del contenido, representado como cadena habitual,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen SVG. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contenido | java.lang.String | Contenido como una cadena habitual, que contiene un contenido SVG válido y compatible con XML. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido SVG, se lanzará una excepción. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Crea una nueva instancia de SvgImage a partir del contenido, representado como flujo de bytes,
y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre de la imagen SVG. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Realiza una verificación superficial de si el contenido textual especificado, compatible con XML
representa una imagen SVG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contenido | java.lang.String | Contenido XML de una imagen SVG como texto simple, no como contenido codificado en base64 |
|

**Returns:**
booleano - Verdadero si la cadena especificada puede considerarse un SVG válido a primera vista, falso si definitivamente no es SVG

### getType() {#getType--}
```
public ImageType getType()
```


Devuelve ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Devuelve el contenido de esta imagen SVG como un flujo binario


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Devuelve el contenido de esta imagen SVG como texto plano (en formato XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Devuelve el contenido de esta imagen SVG en su formato original compatible con XML
forma textual


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Guarda esta imagen SVG en el archivo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado (si no existe) o sobrescrito (si existe) con el contenido de esta imagen SVG |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Guarda esta imagen SVG vectorial en una imagen PNG rasterizada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flujo de salida, en el que se escribirá el contenido de la imagen PNG. No puede ser NULL y debe ser escribible. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Descarta esta imagen rasterizada, descartando su contenido y haciendo que la mayoría de los métodos
y propiedades no funcionales


