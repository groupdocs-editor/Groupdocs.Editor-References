---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un recurso de audio de formato arbitrario."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Representa un recurso de audio de formato arbitrario.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Crea una nueva clase Mp3Audio a partir de contenido MP3, representado como flujo de bytes, y con el nombre especificado |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Verifica si el flujo especificado es un contenido MP3 válido |
|
|  | [getName()](#getName--) | Devuelve el nombre de este contenido MP3. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Devuelve el nombre de archivo correcto de este contenido MP3, que consiste en nombre y extensión. |
|
|  | [getType()](#getType--) | Devuelve un AudioFormat.Mp3 (también satisface IHtmlResource.getFormat() mediante retorno covariante) |
|
|  | [getByteContent()](#getByteContent--) | Devuelve el contenido de esta fuente como flujo de bytes |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Devuelve el contenido de este recurso de audio MP3 como flujo de bytes con la posición original |
|
|  | [getTextContent()](#getTextContent--) | Devuelve el contenido de este recurso MP3 como cadena codificada en base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Guarda este recurso MP3 en el archivo especificado |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
|
|  | [dispose()](#dispose--) | Elimina este recurso MP3, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
|
|  | [isDisposed()](#isDisposed--) | Determina si el contenido MP3 está eliminado o no |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Crea una nueva clase Mp3Audio a partir de contenido MP3, representado como flujo de bytes, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre del contenido MP3. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y desplazable. Si esta instancia se elimina, este flujo también se eliminará. |
|
|  | leaveOpen | boolean | Determina si se elimina o no el flujo especificado cuando la instancia de Mp3Audio se elimina |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Verifica si el flujo especificado es un contenido MP3 válido


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Flujo de bytes que presumiblemente contiene un contenido MP3 |
|

**Returns:**
booleano - Verdadero si el flujo especificado contiene contenido MP3 válido, falso en caso contrario

### getName() {#getName--}
```
public String getName()
```


Devuelve el nombre de este contenido MP3. Normalmente no contiene la extensión del nombre de archivo y, teóricamente, puede diferir del nombre de archivo.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Devuelve el nombre de archivo correcto de este contenido MP3, que consiste en el nombre y la extensión. Teóricamente puede diferir del nombre.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Devuelve un AudioFormat.Mp3 (también satisface IHtmlResource.getFormat() mediante retorno covariante)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Devuelve el contenido de esta fuente como flujo de bytes


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Devuelve el contenido de este recurso de audio MP3 como flujo de bytes con la posición original


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Devuelve el contenido de este recurso MP3 como una cadena codificada en base64. Este valor se almacena en caché después de la primera invocación.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Guarda este recurso MP3 en el archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Ruta completa al archivo, que será creado o sobrescrito. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Otro heredero de la interfaz IHtmlResource |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Otra instancia de la clase Mp3Audio |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### dispose() {#dispose--}
```
public void dispose()
```


Elimina este recurso MP3, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Determina si el contenido MP3 está eliminado o no


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

