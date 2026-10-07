---
title: "TextResourceBase"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Classe base per qualsiasi risorsa testuale supportata con contenuto testuale e codifica"
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Classe base per qualsiasi risorsa testuale supportata con contenuto testuale e codifica

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Crea una nuova risorsa di testo dal contenuto testuale specificato con codifica |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Crea una nuova risorsa di testo dal flusso di byte specificato e codifica |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Restituisce il nome di questa risorsa di testo senza estensione del file |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Restituisce il nome file corretto di questa risorsa di testo, che consiste nel nome |
e estensione
|
|  | [getEncoding()](#getEncoding--) | Restituisce la codifica di questa risorsa testuale. |
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questa risorsa di testo come flusso di byte con l'originale |
codifica
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questa risorsa di testo come stringa standard |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questa risorsa di testo nel file specificato |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Verifica questa istanza con quella specificata per l'uguaglianza. |
|
|  | [dispose()](#dispose--) | Dispone di questa risorsa di testo, eliminando il suo contenuto e rendendo la maggior parte |
dei metodi e delle proprietà non funzionanti.
|
|  | [isDisposed()](#isDisposed--) | Determina se questa risorsa di testo è stata disposata o meno |
|
|  | [getType()](#getType--) | Nel tipo di implementazione dovrebbe restituire informazioni sul tipo del testo |
risorsa
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Crea una nuova risorsa di testo dal contenuto testuale specificato con codifica


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome obbligatorio della risorsa, che funge da identificatore unico. Solitamente è un nome file. |
|
|  | textualContent | java.lang.String | Contenuto testuale della risorsa, non può essere NULL o vuoto |
|
|  | originalEncoding | java.nio.charset.Charset | Codifica originale della risorsa, non può essere NULL o vuoto |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Crea una nuova risorsa di testo dal flusso di byte specificato e codifica


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome obbligatorio della risorsa, che funge da identificatore unico. Solitamente è un nome file. |
|
|  | binaryContent | java.io.InputStream | Contenuto binario di una risorsa come flusso di byte. Non può essere NULL, disposato, dovrebbe essere leggibile e ricercabile. |
|
|  | originalEncoding | java.nio.charset.Charset | Codifica originale della risorsa, non può essere NULL o vuoto |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome di questa risorsa di testo senza estensione del file


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Restituisce il nome file corretto di questa risorsa di testo, che consiste nel nome
e estensione


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Restituisce la codifica di questa risorsa testuale. Solitamente restituisce UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Restituisce il contenuto di questa risorsa di testo come flusso di byte con l'originale
codifica


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Restituisce il contenuto di questa risorsa di testo come stringa standard


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Salva questa risorsa di testo nel file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo del file, che verrà creato o riscritto se esiste già |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Verifica questa istanza con quella specificata per l'uguaglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Altra risorsa HTML di tipo sconosciuto, che è presumibilmente anche erede di TextResourceBase |
|

**Returns:**
boolean - Restituisce true se sono uguali, o false se sono diversi

### dispose() {#dispose--}
```
public final void dispose()
```


Dispone di questa risorsa di testo, eliminando il suo contenuto e rendendo la maggior parte
metodi e proprietà non funzionanti. Tollerante a chiamate multiple.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina se questa risorsa di testo è stata disposata o meno


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Nel tipo di implementazione dovrebbe restituire informazioni sul tipo del testo
risorsa


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
