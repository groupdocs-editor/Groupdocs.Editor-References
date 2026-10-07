---
title: "IHtmlResource"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un'istanza della risorsa HTML sconosciuta raster o vettoriale, immagine, foglio di stile, font, risorsa di testo, CSS, XML, ecc."
type: docs
weight: 12
url: /it/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Rappresenta un'istanza della risorsa HTML sconosciuta (raster o immagine vettoriale,
foglio di stile, font, risorsa di testo (CSS, XML) ecc.)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Nome della risorsa HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Nome file corretto della risorsa specificata con il file appropriato |
estensione
|
|  | [getType()](#getType--) | Tipo della risorsa HTML |
|
|  | [getByteContent()](#getByteContent--) | Contenuto della risorsa HTML sotto forma di flusso di byte |
|
|  | [getTextContent()](#getTextContent--) | Contenuto della risorsa HTML sotto forma di stringa di testo codificata base64 |
per risorse binarie o un semplice testo per risorse testuali
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva una risorsa corrente nel file specificato |
|
### getName() {#getName--}
```
public abstract String getName()
```


Nome della risorsa HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Nome file corretto della risorsa specificata con il file appropriato
estensione


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Tipo della risorsa HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Contenuto della risorsa HTML sotto forma di flusso di byte


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Contenuto della risorsa HTML sotto forma di stringa di testo codificata base64
per risorse binarie o un semplice testo per risorse testuali


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Salva una risorsa corrente nel file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo del file, che sarà creato o sovrascritto con il contenuto di una risorsa corrente |
|

