---
title: "TextResourceBase"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Clase base para cualquier recurso de texto compatible con contenido textual y codificación."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Clase base para cualquier recurso de texto compatible con contenido textual y codificación.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Crea un nuevo recurso de texto a partir del contenido textual especificado con codificación |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Crea un nuevo recurso de texto a partir del flujo de bytes especificado y codificación |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [Disposed](#Disposed) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Devuelve el nombre de este recurso de texto sin la extensión del archivo |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Devuelve el nombre de archivo correcto de este recurso de texto, que consiste en el nombre |
y la extensión
|
|  | [getEncoding()](#getEncoding--) | Devuelve la codificación de este recurso textual. |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de este recurso de texto como flujo de bytes con el original |
codificación
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de este recurso de texto como una cadena estándar |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda este recurso de texto en el archivo especificado |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con la especificada para igualdad. |
|
|  | [dispose()](#dispose--) | Elimina este recurso de texto, eliminando su contenido y haciendo que la mayoría |
de los métodos y propiedades dejen de funcionar.
|
|  | [isDisposed()](#isDisposed--) | Determina si este recurso de texto está eliminado o no |
|
|  | [getType()](#getType--) | En la implementación, el tipo debe devolver información sobre el tipo de texto |
recurso
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Crea un nuevo recurso de texto a partir del contenido textual especificado con codificación


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre obligatorio del recurso, que sirve como su identificador único. Normalmente es un nombre de archivo. |
|
|  | textualContent | java.lang.String | Contenido textual del recurso, no puede ser NULL o estar vacío |
|
|  | originalEncoding | java.nio.charset.Charset | Codificación original del recurso, no puede ser NULL o estar vacío |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Crea un nuevo recurso de texto a partir del flujo de bytes especificado y codificación


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre obligatorio del recurso, que sirve como su identificador único. Normalmente es un nombre de archivo. |
|
|  | binaryContent | java.io.InputStream | Contenido binario de un recurso como flujo de bytes. No puede ser NULL, estar eliminado, debe ser legible y buscable. |
|
|  | originalEncoding | java.nio.charset.Charset | Codificación original del recurso, no puede ser NULL o estar vacío |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Devuelve el nombre de este recurso de texto sin la extensión del archivo


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Devuelve el nombre de archivo correcto de este recurso de texto, que consiste en el nombre
y la extensión


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Devuelve la codificación de este recurso textual. Normalmente devuelve UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Devuelve el contenido de este recurso de texto como flujo de bytes con el original
codificación


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Devuelve el contenido de este recurso de texto como una cadena estándar


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Guarda este recurso de texto en el archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado o sobrescrito si ya existe |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Comprueba esta instancia con la especificada para igualdad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otro recurso HTML de tipo desconocido, que también es presumiblemente heredero de TextResourceBase |
|

**Returns:**
boolean - Devuelve true si son iguales, o false si son diferentes

### dispose() {#dispose--}
```
public final void dispose()
```


Elimina este recurso de texto, eliminando su contenido y haciendo que la mayoría
los métodos y propiedades dejan de funcionar. Tolerante a múltiples llamadas.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina si este recurso de texto está eliminado o no


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


En la implementación, el tipo debe devolver información sobre el tipo de texto
recurso


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
