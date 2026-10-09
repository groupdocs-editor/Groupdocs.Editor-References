---
title: "RasterImageResourceBase"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Clase base para cualquier imagen raster soportada con nombre, dimensiones, relación de aspecto, tipo, tamaño y contenido fijos."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Clase base para cualquier imagen raster soportada con nombre, dimensiones, aspecto
relación, tipo, tamaño y contenido.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [Disposed](#Disposed) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Devuelve el nombre de esta imagen raster. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Devuelve el nombre de archivo correcto de esta imagen raster, que consiste en el nombre y |
extensión.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Devuelve las dimensiones lineales de esta imagen raster (ancho y alto) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Devuelve una relación de aspecto de esta imagen como la relación ancho/alto |
|
|  | [getLength()](#getLength--) | Devuelve la longitud de este archivo de imagen raster en bytes |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta imagen raster como flujo de bytes |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de esta imagen raster como cadena codificada en base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda esta imagen raster en el archivo especificado |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con la especificada por igualdad de referencia. |
|
|  | [dispose()](#dispose--) | Descarta esta imagen raster, descartando su contenido y haciendo que la mayoría de los métodos |
y propiedades no funcionen
|
|  | [isDisposed()](#isDisposed--) | Determina si esta imagen raster está descartada o no |
|
|  | [getType()](#getType--) | En la implementación, el tipo debe devolver información sobre el tipo del raster |
imagen
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Devuelve el nombre de esta imagen raster. Normalmente no contiene el nombre de archivo
extensión y, teóricamente, puede diferir del nombre de archivo.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Devuelve el nombre de archivo correcto de esta imagen raster, que consiste en el nombre y
extensión. Teóricamente puede diferir del nombre.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Devuelve las dimensiones lineales de esta imagen raster (ancho y alto)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Devuelve una relación de aspecto de esta imagen como la relación ancho/alto


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Devuelve la longitud de este archivo de imagen raster en bytes


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Devuelve el contenido de esta imagen raster como flujo de bytes


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Devuelve el contenido de esta imagen raster como cadena codificada en base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Guarda esta imagen raster en el archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado o sobrescrito |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Comprueba esta instancia con la especificada por igualdad de referencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otro heredero de IHtmlResource |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### dispose() {#dispose--}
```
public final void dispose()
```


Descarta esta imagen raster, descartando su contenido y haciendo que la mayoría de los métodos
y propiedades no funcionen


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


En la implementación, el tipo debe devolver información sobre el tipo del raster
imagen


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
