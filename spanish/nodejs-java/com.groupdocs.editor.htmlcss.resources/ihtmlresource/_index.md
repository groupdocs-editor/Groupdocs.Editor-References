---
title: "IHtmlResource"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa una instancia del recurso HTML desconocido raster o vector, imagen, hoja de estilo, fuente, texto, recurso CSS, XML, etc."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Representa una instancia del recurso HTML desconocido (raster o vector imagen,
hoja de estilo, fuente, recurso de texto (CSS, XML), etc.)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Nombre del recurso HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Nombre de archivo correcto del recurso especificado con el archivo apropiado |
extensión
|
|  | [getType()](#getType--) | Tipo del recurso HTML |
|
|  | [getByteContent()](#getByteContent--) | Contenido del recurso HTML en forma de flujo de bytes |
|
|  | [getTextContent()](#getTextContent--) | Contenido del recurso HTML en forma de cadena de texto codificada en base64 |
para recursos binarios o un texto simple para recursos textuales
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda un recurso actual en el archivo especificado |
|
### getName() {#getName--}
```
public abstract String getName()
```


Nombre del recurso HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Nombre de archivo correcto del recurso especificado con el archivo apropiado
extensión


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Tipo del recurso HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Contenido del recurso HTML en forma de flujo de bytes


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Contenido del recurso HTML en forma de cadena de texto codificada en base64
para recursos binarios o un texto simple para recursos textuales


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Guarda un recurso actual en el archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado o sobrescrito con el contenido de un recurso actual |
|

