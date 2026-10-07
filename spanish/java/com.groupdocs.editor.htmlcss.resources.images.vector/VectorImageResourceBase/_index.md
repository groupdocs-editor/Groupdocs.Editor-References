---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Clase base para cualquier imagen vectorial compatible"
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
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
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
|
|  | [isDisposed()](#isDisposed--) | Determina si esta imagen raster está descartada o no |
|
|  | [getType()](#getType--) | En el tipo de implementación debe devolver información sobre el tipo del vector |
imagen
|
|  | [getByteContent()](#getByteContent--) | En el tipo de implementación debe devolver el contenido de esta imagen vectorial como byte |
stream
|
|  | [getTextContent()](#getTextContent--) | En el tipo de implementación debe devolver el contenido de esta imagen vectorial en texto |
form: codificado en base64 de XML relativo al tipo de imagen
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | En el tipo de implementación debe guardar esta imagen en el disco mediante la ruta especificada |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | En el tipo de implementación debe guardar la imagen vectorial actual en el PNG rasterizado |
formatear en el flujo de bytes especificado
|
|  | [dispose()](#dispose--) | En el tipo de implementación debe disponer de esta instancia |
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


Comprueba esta instancia con la especificada mediante igualdad de referencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otra instancia de imagen vectorial |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

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


En el tipo de implementación debe devolver información sobre el tipo del vector
imagen


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


En el tipo de implementación debe devolver el contenido de esta imagen vectorial como byte
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


En el tipo de implementación debe devolver el contenido de esta imagen vectorial en texto
form: codificado en base64 de XML relativo al tipo de imagen


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


En el tipo de implementación debe guardar esta imagen en el disco mediante la ruta especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


En el tipo de implementación debe guardar la imagen vectorial actual en el PNG rasterizado
formatear en el flujo de bytes especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flujo de bytes, en el que se almacenará la versión PNG de esta imagen rasterizada. No debe ser NULL y debe soportar escritura. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


En el tipo de implementación debe disponer de esta instancia


