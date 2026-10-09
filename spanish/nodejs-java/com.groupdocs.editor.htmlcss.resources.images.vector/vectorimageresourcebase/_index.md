---
title: "VectorImageResourceBase"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Clase base para cualquier imagen vectorial compatible"
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Clase base para cualquier imagen vectorial compatible

## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [Disposed](#Disposed) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Devuelve el nombre de esta imagen vectorial. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Devuelve el nombre de archivo correcto de esta imagen vectorial, que consiste en el nombre y |
extensión.
|
|  | [getAspectRatio()](#getAspectRatio--) | Devuelve la relación de aspecto de esta imagen vectorial |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Devuelve las dimensiones lineales de esta imagen vectorial (ancho y alto) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con la especificada por igualdad de referencia. |
|
|  | [isDisposed()](#isDisposed--) | Determina si esta imagen raster está descartada o no |
|
|  | [getType()](#getType--) | En la implementación, el tipo debe devolver información sobre el tipo del vector |
imagen
|
|  | [getByteContent()](#getByteContent--) | En la implementación, el tipo debe devolver el contenido de esta imagen vectorial como bytes |
flujo
|
|  | [getTextContent()](#getTextContent--) | En la implementación, el tipo debe devolver el contenido de esta imagen vectorial en texto |
formato: codificado en base64 de XML relativo al tipo de imagen
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | En la implementación, el tipo debe guardar esta imagen en el disco en la ruta especificada |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | En la implementación, el tipo debe guardar la imagen vectorial actual en el raster PNG |
formatear en el flujo de bytes especificado
|
|  | [dispose()](#dispose--) | En la implementación, el tipo debe descartar esta instancia |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Devuelve el nombre de esta imagen vectorial. Normalmente no contiene el nombre de archivo
extensión y, teóricamente, puede diferir del nombre de archivo.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Devuelve el nombre de archivo correcto de esta imagen vectorial, que consiste en el nombre y
extensión. Teóricamente puede diferir del nombre.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Devuelve la relación de aspecto de esta imagen vectorial


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Devuelve las dimensiones lineales de esta imagen vectorial (ancho y alto)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Comprueba esta instancia con la especificada por igualdad de referencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otra instancia de imagen vectorial |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina si esta imagen raster está descartada o no


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


En la implementación, el tipo debe devolver información sobre el tipo del vector
imagen


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


En la implementación, el tipo debe devolver el contenido de esta imagen vectorial como bytes
flujo


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


En la implementación, el tipo debe devolver el contenido de esta imagen vectorial en texto
formato: codificado en base64 de XML relativo al tipo de imagen


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


En la implementación, el tipo debe guardar esta imagen en el disco en la ruta especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


En la implementación, el tipo debe guardar la imagen vectorial actual en el raster PNG
formatear en el flujo de bytes especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flujo de bytes, en el que se almacenará la versión PNG de esta imagen raster. No debe ser NULL y debe soportar escritura. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


En la implementación, el tipo debe descartar esta instancia


