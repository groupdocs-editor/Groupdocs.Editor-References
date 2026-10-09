---
title: "FontResourceBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Classe base per qualsiasi tipo di font supportato come risorsa per il documento HTML con tutte le sue proprietà"
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Classe base per qualsiasi tipo di font supportato come risorsa per il documento HTML
con tutte le sue proprietà

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Disposed](#Disposed) | Evento, che si verifica quando questo font viene eliminato |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Restituisce il nome di questa risorsa font. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Restituisce il nome file corretto di questa risorsa font, che consiste nel nome |
e nell'estensione.
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questo font come flusso di byte |
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questo font come stringa codificata in base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questo font nel file specificato |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Verifica questa istanza con la risorsa HTML specificata per uguaglianza di riferimento |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Verifica questa istanza con la risorsa font specificata per uguaglianza di riferimento |
|
|  | [dispose()](#dispose--) | Elimina questa risorsa font, liberando il suo contenuto e rendendo la maggior parte |
metodi e proprietà non funzionanti
|
|  | [isDisposed()](#isDisposed--) | Determina se questo font è stato eliminato o meno |
|
|  | [getType()](#getType--) | Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di specifico |
risorsa font come istanza di un tipo specifico FontType, che
incapsula tutte le informazioni specifiche del tipo
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Evento, che si verifica quando questo font viene eliminato


### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome di questa risorsa font. Di solito non contiene il nome file
estensione e teoricamente può differire dal nome file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Restituisce il nome file corretto di questa risorsa font, che consiste nel nome
e l'estensione. Teoricamente può differire dal nome.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Restituisce il contenuto di questo font come flusso di byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Restituisce il contenuto di questo font come stringa codificata in base64. Questo valore è
memorizzato nella cache dopo la prima invocazione.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Salva questo font nel file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo al file, che sarà creato o riscritto |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Verifica questa istanza con la risorsa HTML specificata per uguaglianza di riferimento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Altro erede dell'interfaccia IHtmlResource |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Verifica questa istanza con la risorsa font specificata per uguaglianza di riferimento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Altro erede della classe astratta FontResourceBase |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### dispose() {#dispose--}
```
public final void dispose()
```


Elimina questa risorsa font, liberando il suo contenuto e rendendo la maggior parte
metodi e proprietà non funzionanti


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina se questo font è stato eliminato o meno


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di specifico
risorsa font come istanza di un tipo specifico FontType, che
incapsula tutte le informazioni specifiche del tipo


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
