---
title: "Mp3Audio"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta una risorsa audio di formato arbitrario"
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Rappresenta una risorsa audio di formato arbitrario

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Crea una nuova classe Mp3Audio dal contenuto MP3, rappresentato come flusso di byte, e con il nome specificato |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Verifica se il flusso specificato è un contenuto MP3 valido |
|
|  | [getName()](#getName--) | Restituisce il nome di questo contenuto MP3. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Restituisce il nome file corretto di questo contenuto MP3, che consiste di nome ed estensione. |
|
|  | [getType()](#getType--) | Restituisce un AudioFormat.Mp3 (soddisfa anche IHtmlResource.getFormat() tramite ritorno covariante) |
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questo font come flusso di byte |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Restituisce il contenuto di questa risorsa audio MP3 come flusso di byte con la posizione originale |
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questa risorsa MP3 come stringa codificata in base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questa risorsa MP3 nel file specificato |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Verifica questa istanza con la risorsa HTML specificata per uguaglianza di riferimento |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Verifica questa istanza con la risorsa font specificata per uguaglianza di riferimento |
|
|  | [dispose()](#dispose--) | Rilascia questa risorsa MP3, eliminando il suo contenuto e rendendo la maggior parte dei metodi e delle proprietà non funzionanti |
|
|  | [isDisposed()](#isDisposed--) | Determina se questo contenuto MP3 è stato rilasciato o meno |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Crea una nuova classe Mp3Audio dal contenuto MP3, rappresentato come flusso di byte, e con il nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome del contenuto MP3. Non può essere nullo, vuoto o contenere solo spazi. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|
|  | leaveOpen | boolean | Determina se rilasciare o meno il flusso specificato quando l'istanza Mp3Audio viene rilasciata |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Verifica se il flusso specificato è un contenuto MP3 valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Flusso di byte, che presumibilmente contiene un contenuto MP3 |
|

**Returns:**
boolean - True se il flusso specificato contiene un contenuto MP3 valido, false altrimenti

### getName() {#getName--}
```
public String getName()
```


Restituisce il nome di questo contenuto MP3. Di solito non contiene l'estensione del nome file e teoricamente può differire dal nome file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Restituisce il nome file corretto di questo contenuto MP3, che è composto da nome ed estensione. Teoricamente può differire dal nome.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Restituisce un AudioFormat.Mp3 (soddisfa anche IHtmlResource.getFormat() tramite ritorno covariante)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Restituisce il contenuto di questo font come flusso di byte


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Restituisce il contenuto di questa risorsa audio MP3 come flusso di byte con la posizione originale


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Restituisce il contenuto di questa risorsa MP3 come stringa codificata in base64. Questo valore è memorizzato nella cache dopo la prima invocazione.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Salva questa risorsa MP3 nel file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo del file, che verrà creato o riscritto |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Verifica questa istanza con la risorsa HTML specificata per uguaglianza di riferimento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Altro erede dell'interfaccia IHtmlResource |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Verifica questa istanza con la risorsa font specificata per uguaglianza di riferimento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Altra istanza della classe Mp3Audio |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### dispose() {#dispose--}
```
public void dispose()
```


Rilascia questa risorsa MP3, eliminando il suo contenuto e rendendo la maggior parte dei metodi e delle proprietà non funzionanti


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Determina se questo contenuto MP3 è stato rilasciato o meno


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

