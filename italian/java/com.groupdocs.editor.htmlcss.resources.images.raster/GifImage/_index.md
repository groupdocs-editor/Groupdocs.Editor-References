---
title: "GifImage"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un'immagine nel formato GIF Graphics Interchange Format con i relativi metadati e metodi aggiuntivi"
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Rappresenta un'immagine nel formato GIF (Graphics Interchange Format) con il suo
metadati e metodi aggiuntivi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Crea una nuova istanza di GifImage dal contenuto, rappresentato come base64 codificato |
stringa, e con nome specificato
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Crea una nuova istanza di GifImage dal contenuto, rappresentato come flusso di byte, |
e con nome specificato
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Verifica se il flusso specificato è un'immagine GIF valida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Verifica se la stringa codificata in base64 specificata è un'immagine GIF valida |
|
|  | [getType()](#getType--) | Restituisce ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Restituisce la versione interna di questa immagine GIF (la versione è estratta da |
intestazione)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Crea una nuova istanza di GifImage dal contenuto, rappresentato come base64 codificato
stringa, e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine GIF. Non può essere nullo, vuoto o contenere spazi. |
|
|  | contentInBase64 | java.lang.String | Contenuto come stringa codificata in base64. Non può essere nullo, vuoto o contenere spazi. Se non è un contenuto GIF, verrà sollevata un'eccezione. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Crea una nuova istanza di GifImage dal contenuto, rappresentato come flusso di byte,
e con nome specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'immagine GIF. Non può essere nullo, vuoto o contenere spazi. |
|
|  | binaryContent | java.io.InputStream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Deve essere leggibile e ricercabile. Se questa istanza verrà rilasciata, anche questo flusso verrà rilasciato. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Verifica se il flusso specificato è un'immagine GIF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flusso di byte, che presumibilmente contiene un'immagine GIF |
|

**Returns:**
boolean - True se il flusso specificato contiene un'immagine GIF valida, false altrimenti

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Verifica se la stringa codificata in base64 specificata è un'immagine GIF valida


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenuto dell'immagine GIF presumibilmente in forma di stringa codificata in base64 |
|

**Returns:**
boolean - True se la stringa specificata contiene un'immagine GIF valida, false altrimenti

### getType() {#getType--}
```
public ImageType getType()
```


Restituisce ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Restituisce la versione interna di questa immagine GIF (la versione è estratta da
intestazione)


**Returns:**
java.lang.String
