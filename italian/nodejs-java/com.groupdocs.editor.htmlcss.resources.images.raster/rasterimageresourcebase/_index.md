---
title: "RasterImageResourceBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Classe base per qualsiasi immagine raster supportata con nome, dimensioni, rapporto d'aspetto, tipo, dimensione e contenuto fissi."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Classe base per qualsiasi immagine raster supportata con nome, dimensioni, aspetto
rapporto, tipo, dimensione e contenuto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Restituisce il nome di questa immagine raster. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Restituisce il nome file corretto di questa immagine raster, che consiste di nome e |
estensione.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Restituisce le dimensioni lineari di questa immagine raster (larghezza e altezza) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Restituisce un rapporto d'aspetto di questa immagine come relazione larghezza-altezza |
|
|  | [getLength()](#getLength--) | Restituisce la lunghezza di questo file immagine raster in byte |
|
|  | [getByteContent()](#getByteContent--) | Restituisce il contenuto di questa immagine raster come flusso di byte |
|
|  | [getTextContent()](#getTextContent--) | Restituisce il contenuto di questa immagine raster come stringa codificata in base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Salva questa immagine raster nel file specificato |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Verifica questa istanza con quella specificata per uguaglianza di riferimento. |
|
|  | [dispose()](#dispose--) | Dispone di questa immagine raster, disponendo il suo contenuto e rendendo la maggior parte dei metodi |
e le proprietà non funzionanti
|
|  | [isDisposed()](#isDisposed--) | Determina se questa immagine raster è stata eliminata o meno |
|
|  | [getType()](#getType--) | Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di raster |
immagine
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


Restituisce il nome di questa immagine raster. Di solito non contiene il nome file
estensione e teoricamente può differire dal nome file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Restituisce il nome file corretto di questa immagine raster, che consiste di nome e
estensione. Teoricamente può differire dal nome.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Restituisce le dimensioni lineari di questa immagine raster (larghezza e altezza)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Restituisce un rapporto d'aspetto di questa immagine come relazione larghezza-altezza


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Restituisce la lunghezza di questo file immagine raster in byte


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Restituisce il contenuto di questa immagine raster come flusso di byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Restituisce il contenuto di questa immagine raster come stringa codificata in base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Salva questa immagine raster nel file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Percorso completo al file, che sarà creato o riscritto |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Verifica questa istanza con quella specificata per uguaglianza di riferimento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Altro erede di IHtmlResource |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### dispose() {#dispose--}
```
public final void dispose()
```


Dispone di questa immagine raster, disponendo il suo contenuto e rendendo la maggior parte dei metodi
e le proprietà non funzionanti


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


Nel tipo di implementazione dovrebbe restituire informazioni sul tipo di raster
immagine


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
