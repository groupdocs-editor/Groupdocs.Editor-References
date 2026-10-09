---
title: "VectorImageResourceBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Classe base per qualsiasi immagine vettoriale supportata"
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Classe base per qualsiasi immagine vettoriale supportata

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Restituisce il nome di questa immagine vettoriale. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Restituisce il nome file corretto di questa immagine vettoriale, che è composto da nome e |
estensione.
|
|  | [getAspectRatio()](#getAspectRatio--) | Restituisce il rapporto d'aspetto di questa immagine vettoriale |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Restituisce le dimensioni lineari di questa immagine vettoriale (larghezza e altezza) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Verifica questa istanza con quella specificata per uguaglianza di riferimento. |
|
|  | [isDisposed()](#isDisposed--) | Determina se questa immagine raster è stata eliminata o meno |
|
|  | [getType()](#getType--) | Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di vettoriale |
immagine
|
|  | [getByteContent()](#getByteContent--) | Nel tipo di implementazione dovrebbe restituire il contenuto di questa immagine vettoriale come byte |
flusso
|
|  | [getTextContent()](#getTextContent--) | Nel tipo di implementazione dovrebbe restituire il contenuto di questa immagine vettoriale in testo |
formato: base64 codificato di XML relativo al tipo di immagine
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Nel tipo di implementazione dovrebbe salvare questa immagine su disco nel percorso specificato |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Nel tipo di implementazione dovrebbe salvare l'immagine vettoriale corrente in raster PNG |
formato nel flusso di byte specificato
|
|  | [dispose()](#dispose--) | Nel tipo di implementazione dovrebbe eliminare questa istanza |
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


Restituisce il nome di questa immagine vettoriale. Di solito non contiene il nome file
estensione e teoricamente può differire dal nome file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Restituisce il nome file corretto di questa immagine vettoriale, che è composto da nome e
estensione. Teoricamente può differire dal nome.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Restituisce il rapporto d'aspetto di questa immagine vettoriale


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Restituisce le dimensioni lineari di questa immagine vettoriale (larghezza e altezza)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Verifica questa istanza con quella specificata per uguaglianza di riferimento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Altra istanza di immagine vettoriale |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina se questa immagine raster è stata eliminata o meno


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di vettoriale
immagine


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Nel tipo di implementazione dovrebbe restituire il contenuto di questa immagine vettoriale come byte
flusso


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Nel tipo di implementazione dovrebbe restituire il contenuto di questa immagine vettoriale in testo
formato: base64 codificato di XML relativo al tipo di immagine


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Nel tipo di implementazione dovrebbe salvare questa immagine su disco nel percorso specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Nel tipo di implementazione dovrebbe salvare l'immagine vettoriale corrente in raster PNG
formato nel flusso di byte specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flusso di byte, nel quale verrà memorizzata la versione PNG di questa immagine raster. Non deve essere NULL e deve supportare la scrittura. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Nel tipo di implementazione dovrebbe eliminare questa istanza


