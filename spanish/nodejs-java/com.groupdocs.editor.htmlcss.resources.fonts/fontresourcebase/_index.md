---
title: "FontResourceBase"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Clase base para cualquier tipo de fuente compatible como recurso del documento HTML con todas sus propiedades"
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Clase base para cualquier tipo de fuente compatible como recurso del documento HTML
con todas sus propiedades

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Disposed](#Disposed) | Evento, que ocurre cuando esta fuente se elimina |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Devuelve el nombre de este recurso de fuente. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Devuelve el nombre de archivo correcto de este recurso de fuente, que consiste en el nombre |
y la extensión.
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta fuente como flujo de bytes |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de esta fuente como una cadena codificada en base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda esta fuente en el archivo especificado |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
|
|  | [dispose()](#dispose--) | Elimina este recurso de fuente, liberando su contenido y haciendo la mayor parte |
métodos y propiedades no funcionen
|
|  | [isDisposed()](#isDisposed--) | Determina si esta fuente está eliminada o no |
|
|  | [getType()](#getType--) | En la implementación, el tipo debe devolver información sobre el tipo de |
recurso de fuente como una instancia del tipo FontType específico, que
encapsula toda la información específica del tipo
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Evento, que ocurre cuando esta fuente se elimina


### getName() {#getName--}
```
public final String getName()
```


Devuelve el nombre de este recurso de fuente. Normalmente no contiene el nombre de archivo
extensión y, teóricamente, puede diferir del nombre de archivo.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Devuelve el nombre de archivo correcto de este recurso de fuente, que consiste en el nombre
y la extensión. Teóricamente puede diferir del nombre.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Devuelve el contenido de esta fuente como flujo de bytes


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Devuelve el contenido de esta fuente como una cadena codificada en base64. Este valor es
almacenado en caché después de la primera invocación.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Guarda esta fuente en el archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado o sobrescrito |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otro heredero de la interfaz IHtmlResource |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Otro heredero de la clase abstracta FontResourceBase |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### dispose() {#dispose--}
```
public final void dispose()
```


Elimina este recurso de fuente, liberando su contenido y haciendo la mayor parte
métodos y propiedades no funcionen


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina si esta fuente está eliminada o no


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


En la implementación, el tipo debe devolver información sobre el tipo de
recurso de fuente como una instancia del tipo FontType específico, que
encapsula toda la información específica del tipo


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
